# 2. Identificación de fibras y configuración

## 2.1 Identificación y compatibilidad

Antes de preparar los extremos, identifica la etiqueta del cable, la ficha técnica o la documentación del enlace. **No deduzcas el tipo de fibra solo por el color de la chaqueta.**

| Familia | Identificación habitual | Características orientativas | Uso habitual |
| --- | --- | --- | --- |
| Monomodo (SM) | OS1/OS2; ITU-T G.652.D u otras variantes SM | Núcleo pequeño; revestimiento típico de 125 µm. | Acceso, transporte y telecomunicaciones. |
| Multimodo (MM) | OM1 | Habitualmente 62,5/125 µm. | Instalaciones multimodo heredadas. |
| Multimodo (MM) | OM2 / OM3 / OM4 / OM5 | Habitualmente 50/125 µm; OM3/OM4/OM5 optimizadas para aplicaciones de mayor velocidad; OM5 es banda ancha. | LAN y centros de datos. |

**Compatibilidad:** No mezcles SM con MM ni fibras de diferentes especificaciones como si fueran equivalentes. Empalmes entre tipos distintos, fibras especiales o diámetros no habituales requieren un procedimiento diseñado para esa combinación, equipo compatible y validación técnica.

**Nota:** G.652.D es una especificación de fibra monomodo. ITU-T G.651.1 corresponde a fibra multimodo de índice gradual de 50/125 µm. Las categorías OM son clasificaciones de fibra multimodo; no deben presentarse como sinónimos exactos de una recomendación ITU-T.

## 2.2 Parámetros: qué se fija y qué se adapta

**Corrección técnica importante:** No existe una tabla universal de corriente, tiempo de arco, pre-fusión, overlap, temperatura o tiempo de horno válida para todas las fusionadoras y fibras. Los valores de la versión anterior se retiran como valores obligatorios porque podrían inducir a una configuración incorrecta.

### Valores que deben definirse antes de comenzar

| Parámetro | Cómo establecerlo correctamente | Regla para el principiante |
| --- | --- | --- |
| Programa de fusión | Seleccionar el programa del fabricante para el tipo y combinación de fibra identificados. | No crear ni editar programas personalizados. |
| Modo de alineación | Según equipo: alineación por núcleo o revestimiento, de acuerdo con el tipo de fibra y la recomendación del fabricante. | No cambiar el modo para ocultar errores. |
| Longitud de corte | Según el soporte, portafibra y manual del modelo de fusionadora/cleaver. | No asumir que 10–16 mm sirve para todos los equipos. |
| Ángulo de corte aceptable | Usar el límite de rechazo configurado por el fabricante y el programa seleccionado. | Si aparece error de ángulo, volver a preparar y cortar; no forzar la fusión. |
| Arco y pre-fusión | Los controla el programa; calibrar el arco según el procedimiento y condiciones indicadas por el fabricante. | No ajustar corriente ni tiempos manualmente sin autorización técnica. |
| Overlap / avance | Parámetro interno del programa de fusión. | No fijar 14 µm ni otro valor universal. |
| Manguito y horno | Seleccionar el modo de calentamiento que corresponda al manguito exacto. | Respetar el ciclo del fabricante del manguito y la fusionadora; no imponer 180–200 °C como regla universal. |
| Pérdida estimada | Lectura calculada por la fusionadora, dependiente del equipo y del método de estimación. | No equivale a una medición certificada del enlace. |

## 2.3 Secuencia segura de configuración

1. Identificar fabricante, modelo y versión de firmware de la fusionadora.
2. Identificar la fibra de ambos extremos y confirmar que son compatibles.
3. Seleccionar el programa de fusión recomendado para esa fibra.
4. Comprobar que el programa de calentamiento corresponde al manguito instalado.
5. Ejecutar las comprobaciones o calibraciones que indique el fabricante, especialmente si cambian las condiciones ambientales, los electrodos o el equipo lo solicita.
6. Registrar el programa utilizado y cualquier advertencia del equipo.

**Criterio de aceptación:** Los límites de pérdida, ángulo de corte, fuerza de prueba y criterios de rechazo deben venir de la especificación del proyecto, del fabricante o del estándar aplicable. Si no están definidos, detenerse y solicitar el criterio al responsable técnico.

![Fotografía original de la actividad](../images/foto_04.jpg)
