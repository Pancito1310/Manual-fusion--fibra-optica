# Fusión de Fibra Óptica | Manual técnico y registro de práctica

(｡•̀ᴗ-)✧ **Aprende el procedimiento, trabaja con seguridad y verifica cada empalme.**

Repositorio de documentación técnica sobre una **práctica presencial de preparación, fusión y verificación de fibra óptica**, basada en el manual entregado en formato Word. Está organizado para que estudiantes y operadores principiantes puedan consultar el procedimiento, las precauciones, los materiales, las fallas frecuentes y el registro del trabajo.

> \*\*Enfoque del repositorio:\*\* experiencia práctica realizada presencialmente. No se presenta como una investigación teórica ni se inventan mediciones, parámetros del equipo, resultados o datos que no aparecen en el documento fuente.

## Contenido principal

* [Manual técnico completo](MANUAL_TECNICO.md): conserva las 12 secciones, las tablas, las recomendaciones, los consejos, las advertencias y las referencias del documento.
* [Documento Word original](Manual_Tecnico_Fusion_Fibra_Optica_Original.docx): copia de respaldo de la fuente entregada.
* [Galería fotográfica](#galería-fotográfica): nueve fotografías extraídas del Word original.
* [Documentación por temas](#documentación-por-temas): acceso rápido a cada sección.

## Documentación por temas

|Archivo|Contenido|
|-|-|
|[Objetivo, alcance y condiciones de uso](docs/objetivo_y_alcance.md)|Objetivo de la práctica, alcance y condiciones obligatorias.|
|[Seguridad y preparación del puesto](docs/seguridad_y_preparacion.md)|Riesgos, EPP, materiales de seguridad y reglas preventivas.|
|[Herramientas, equipos y consumibles](docs/herramientas_y_materiales.md)|Fusionadora, cleaver, peladora, alcohol, paños, manguitos e instrumentos.|
|[Identificación de fibras y compatibilidad](docs/identificacion_de_fibras.md)|Identificación SM/MM, categorías y compatibilidad.|
|[Parámetros de fusión](docs/parametros_de_fusion.md)|Valores que deben definirse según fabricante y equipo.|
|[Procedimiento paso a paso](docs/procedimiento_paso_a_paso.md)|Secuencia operativa completa desde la preparación hasta el alojamiento del empalme.|
|[Inspección y verificación](docs/inspeccion_y_verificacion.md)|Inspección visual, pruebas del enlace y aceptación.|
|[Mantenimiento y limpieza](docs/mantenimiento_y_limpieza.md)|Cuidados de cleaver, guías V, mordazas, electrodos, lentes, fusionadora y horno.|
|[Fallas y soluciones](docs/fallas_y_soluciones.md)|Matriz de síntomas, causas posibles y acciones correctivas seguras.|
|[Checklist del operador](docs/checklist_del_operador.md)|Lista de comprobación antes, durante y después del trabajo.|
|[Registro del trabajo](docs/registro_del_trabajo.md)|Datos que deben registrarse para documentar la actividad.|
|[Referencias técnicas](docs/referencias_tecnicas.md)|Fuentes técnicas y documentación de consulta.|

## 

## Alcance y seguridad

* La primera práctica debe realizarse en laboratorio, con fibras de entrenamiento desconectadas de cualquier fuente óptica y bajo supervisión.
* Nunca se debe mirar directamente el extremo de una fibra.
* Antes de abrir, inspeccionar o manipular una fibra de una instalación existente, se debe verificar con un instrumento adecuado que no haya potencia óptica.
* Los fragmentos de fibra deben recogerse con pinzas y depositarse en un recipiente rígido, cerrado y rotulado.
* El alcohol isopropílico es inflamable: debe mantenerse lejos del arco, el horno, chispas y fuentes de calor.
* El manual del fabricante de la fusionadora, cleaver, fibras y manguitos prevalece sobre cualquier valor genérico.
* No existen parámetros universales de corriente, tiempo de arco, overlap, temperatura o tiempo de horno aplicables a todos los equipos y fibras.
* Si un error persiste después de una corrección razonable, se debe detener el trabajo y solicitar apoyo técnico.

## Información técnica importante

El manual cubre fibras monomodo (SM) y multimodo (MM), siempre que la fusionadora, los soportes, el programa y los consumibles sean compatibles. No cubre empalmes mecánicos, conectorización, trabajos en altura, intervención de redes energizadas ni reparación de equipos.

La pérdida estimada que muestra la fusionadora no sustituye la medición del enlace terminado. Según el alcance del trabajo, pueden requerirse fuente de luz y medidor de potencia y/o un OTDR, con el método de prueba definido por el proyecto.

## Cómo utilizar este repositorio

1. Comienza por leer el [manual técnico completo](MANUAL_TECNICO.md).
2. Consulta las secciones individuales de `docs/` cuando necesites revisar un tema concreto.
3. Revisa las fotografías de `images/` como apoyo visual de la práctica presencial.
4. Utiliza el checklist antes, durante y después del procedimiento.
5. Completa el registro del trabajo con datos reales de la práctica. No inventes valores que no hayan sido medidos o registrados.

## Estructura del repositorio

```text
fusion-fibra-optica/
├── README.md
├── MANUAL\_TECNICO.md
├── Manual\_Tecnico\_Fusion\_Fibra\_Optica\_Original.docx
├── .gitignore
├── images/
└── docs/
```

## Versión y origen del contenido

* **Manual:** versión 2.0.
* **Fecha indicada en el documento:** noviembre de 2026.
* **Base documental:** `Manual\_Tecnico\_Fusion\_Fibra\_Optica\_Original.docx`.
* **Fotografías:** extraídas del documento Word proporcionado.
* **Criterio de edición:** organizar la información para GitHub sin eliminar recomendaciones, advertencias, consejos, tablas ni kaomojis del documento fuente.

## Referencias

Las referencias técnicas completas se encuentran en [docs/referencias\_tecnicas.md](docs/referencias_tecnicas.md) y en el [manual completo](MANUAL_TECNICO.md).

\---

**Cierre (づ｡◕◕ ‿ ｡)づ**  
Un buen empalme no depende de memorizar números universales: depende de identificar la fibra, seleccionar el programa correcto, preparar extremos limpios y bien cortados, seguir el fabricante y verificar el resultado.

