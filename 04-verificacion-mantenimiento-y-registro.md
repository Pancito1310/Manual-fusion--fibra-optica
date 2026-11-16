# 4. Verificación, mantenimiento y registro

## 4.1 Inspección visual y del equipo

- Confirmar que el empalme no presente burbujas, grietas, deformaciones o desplazamientos evidentes.
- Confirmar que el manguito esté centrado, completamente contraído y sin bordes que puedan engancharse.
- Registrar el mensaje final y la pérdida estimada por la fusionadora.
- Rechazar y rehacer el empalme si el equipo lo indica o si el resultado no cumple el criterio de aceptación establecido.

## 4.2 Medición del enlace

La pérdida mostrada por la fusionadora es una estimación basada en la imagen y el algoritmo del equipo. No sustituye la medición del enlace terminado. Según el alcance del trabajo, se puede requerir fuente de luz y medidor de potencia para medir pérdida de inserción, y/o OTDR para caracterizar eventos y localizar anomalías. Los equipos deben estar calibrados y utilizar el método, longitud de onda y referencia definidos por el proyecto.

**No inventar un umbral:** No se establece aquí un máximo universal de 0,05 dB por empalme. El límite de aceptación debe definirse en el diseño, contrato, estándar o procedimiento del proyecto y verificarse con el método de prueba indicado.

## 4.3 Mantenimiento básico y limpieza

| Elemento | Acción de mantenimiento | Precaución |
| --- | --- | --- |
| Cleaver | Limpiar cuchilla, yunques y almohadillas según el fabricante; inspeccionar desgaste y calidad de corte. | No tocar el filo ni girar/reemplazar la cuchilla sin seguir el procedimiento del modelo. |
| Guías V y mordazas | Limpiar periódicamente y cuando haya polvo, desplazamiento o errores de posicionamiento, con útiles y líquido autorizados. | No rayar ni aplicar exceso de líquido. |
| Electrodos | Revisar vida útil, mensajes de recambio y procedimiento de estabilización/calibración del fabricante. | No manipular puntas calientes ni doblarlas. Reemplazo solo según manual. |
| Lentes y cámaras | Limpiar solo si el fabricante lo permite y con material apropiado. | No desmontar componentes ópticos sin autorización. |
| Fusionadora y horno | Mantener libres de polvo y residuos; revisar estado de la bandeja y ciclo de calentamiento. | No abrir el equipo ni realizar reparaciones internas. |

Como referencia de buenas prácticas, Fujikura recomienda mantener limpios el cleaver, las guías V y las mordazas, ya que la contaminación puede provocar cortes deficientes, errores de posición y mayores pérdidas. Las frecuencias exactas dependen del modelo y del uso.

## 4.4 Matriz de fallas y acciones correctivas

| Mensaje / síntoma | Causas posibles | Acción segura |
| --- | --- | --- |
| Bad Cleave Angle / ángulo de corte alto | Fibra mal colocada, cleaver sucio o desgastado, longitud de corte incorrecta. | Cancelar. Desechar el extremo cortado en el contenedor. Limpiar e inspeccionar cleaver; preparar y cortar un nuevo extremo. |
| Dust / Fiber Dust / suciedad | Fibra desnuda contaminada, paño reutilizado, guías o lentes sucios. | No fusionar. Repetir limpieza con paño nuevo; limpiar componentes solo según manual. |
| High estimated loss / pérdida estimada alta | Corte deficiente, contaminación, fibras incompatibles, programa incorrecto, arco fuera de calibración. | Revisar identificación y programa; rehacer preparación; ejecutar calibración indicada por fabricante. No modificar corriente o overlap por intuición. |
| Fat splice / empalme abultado | Parámetros de arco inadecuados, fibra no identificada o programa incorrecto. | Detener. Confirmar tipo de fibra y programa. Ejecutar diagnóstico/calibración según manual; no fijar un overlap universal. |
| Thin splice / empalme delgado | Condición de arco inadecuada, extremos mal preparados o programa incorrecto. | Detener y revisar corte, limpieza, compatibilidad y calibración. No aumentar/disminuir corriente manualmente sin procedimiento autorizado. |
| Bubble / burbuja | Contaminación, humedad, cara de corte dañada o condiciones de arco incorrectas. | Desechar el empalme defectuoso, preparar nuevos extremos y confirmar limpieza, secado y programa. |
| Fiber position / motor error | Suciedad en guías o mordazas, fibra mal colocada o problema mecánico. | Cancelar. Limpiar según manual, volver a colocar y repetir una vez. Si persiste, retirar el equipo de servicio y solicitar soporte. |
| Manguito mal contraído | Manguito incompatible, mal centrado o programa de horno incorrecto. | No alojar el empalme. Dejar enfriar; evaluar reemplazo siguiendo el procedimiento del fabricante y verificar el horno. |

**Detención segura (•̀ᴗ•́)و** Si el mismo error persiste después de una corrección razonable, no continúes realizando fusiones de prueba. Registra el error, retira el equipo de servicio si corresponde y consulta al responsable técnico.

## 4.5 Lista de verificación del operador

| Momento | Comprobación | OK / N/A |
| --- | --- | --- |
| Antes | Tengo autorización, capacitación y supervisión requerida. | ☐ |
| Antes | Uso gafas y tengo contenedor de residuos disponible. | ☐ |
| Antes | Confirmé que no existe señal óptica peligrosa en la fibra. | ☐ |
| Antes | Identifiqué ambos tipos de fibra y confirmé compatibilidad. | ☐ |
| Antes | Fusionadora, cleaver, horno y consumibles están en buen estado. | ☐ |
| Configuración | Seleccioné el programa recomendado por fabricante. | ☐ |
| Proceso | Inserté el manguito antes de cortar y fusionar. | ☐ |
| Proceso | Pelé, limpié y corté sin contaminar ni dañar la fibra. | ☐ |
| Proceso | Revisé alineación, alertas y resultado del ciclo. | ☐ |
| Final | Manguito centrado, enfriado y empalme alojado correctamente. | ☐ |
| Final | Realicé las pruebas requeridas y registré resultados. | ☐ |
| Final | Eliminé residuos y limpié el puesto; lavé mis manos. | ☐ |

## 4.6 Registro del trabajo

Completa este registro para dejar constancia de la actividad y sus resultados:

| Dato | Registro |
| --- | --- |
| Fecha / hora | ____________________________________________ |
| Operador / supervisor | ____________________________________________ |
| Ubicación / identificación del enlace | ____________________________________________ |
| Fabricante y modelo de fusionadora | ____________________________________________ |
| Tipo de fibra extremo A / B | ____________________________________________ |
| Programa de fusión utilizado | ____________________________________________ |
| Tipo y longitud de manguito | ____________________________________________ |
| Pérdida estimada en pantalla | ____________________________________________ |
| Prueba final / instrumento / longitud de onda | ____________________________________________ |
| Resultado y observaciones | ____________________________________________ |
| Fotografías / nombre de archivos | ____________________________________________ |

## 4.7 Referencias técnicas

Consultar siempre la versión vigente del manual específico del equipo y las fichas de seguridad de los productos utilizados. Las siguientes fuentes respaldan las recomendaciones generales de seguridad y mantenimiento:

- The Fiber Optic Association (FOA) – Fiber Optic Safety — https://www.thefoa.org/tech/ref/safety/safe.html
- NECA/FOA 301 – Standard for Installing and Testing Fiber Optics (precauciones de seguridad) — https://www.thefoa.org/tech/ref/1pstandards/NECA301-16_P.pdf
- Corning – Standard Recommended Procedure 003-534 (precauciones de seguridad) — https://www.corning.com/catalog/coc/documents/standard-recommended-procedures/003-534.pdf
- Fujikura Europe – How to clean your fusion splicer — https://www.europe.fujikura.com/insights/how-to-clean-your-fusion-splicer/
- Fujikura – Limpieza de cleaver CT50 — https://www.optic-product.fujikura.com/support-resources_services/fusion-splicer-maintenance/how-to-clean-the-clamp-pad-anvil-and-cleaver-blade-of-ct50/
- Fujikura – Limpieza de guías V y mordazas — https://www.optic-product.fujikura.com/support-resources_services/fusion-splicer-maintenance/how-to-clean-vgroove-and-fiber-clamp-chips-of-90s/
- ITU-T G.652 – Characteristics of a single-mode optical fibre and cable — https://www.itu.int/rec/T-REC-G.652/en
- ITU-T G.651.1 – Characteristics of a 50/125 µm multimode graded index optical fibre cable — https://www.itu.int/rec/T-REC-G.651.1/en

## Cierre

(づ｡◕‿‿◕｡)づ Un buen empalme no depende de memorizar números universales: depende de identificar la fibra, seleccionar el programa correcto, preparar extremos limpios y bien cortados, seguir el fabricante y verificar el resultado.
