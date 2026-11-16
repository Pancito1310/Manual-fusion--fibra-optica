#Fusión de Fibra Óptica | Manual técnico y registro de práctica

(｡•̀ᴗ-)✧ **Aprende el procedimiento, trabaja con seguridad y verifica cada empalme.**

Repositorio de documentación técnica sobre una **práctica presencial de preparación, fusión y verificación de fibra óptica**, basada en el manual entregado en formato Word. Está organizado para que estudiantes y operadores principiantes puedan consultar el procedimiento, las precauciones, los materiales, las fallas frecuentes y el registro del trabajo.

> \*\*Enfoque del repositorio:\*\* experiencia práctica realizada presencialmente. No se presenta como una investigación teórica ni se inventan mediciones, parámetros del equipo, resultados o datos.

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
2. Consulta las secciones individuales cuando necesites revisar un tema concreto.
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

## Referencias técnicas
Consultar siempre la versión vigente del manual específico del equipo y las fichas de seguridad de los productos utilizados. Las siguientes fuentes respaldan las recomendaciones generales de seguridad y mantenimiento:
The Fiber Optic Association (FOA) – Fiber Optic Safety — https://www.thefoa.org/tech/ref/safety/safe.html
NECA/FOA 301 – Standard for Installing and Testing Fiber Optics (precauciones de seguridad) — https://www.thefoa.org/tech/ref/1pstandards/NECA301-16_P.pdf
Corning – Standard Recommended Procedure 003-534 (precauciones de seguridad) — https://www.corning.com/catalog/coc/documents/standard-recommended-procedures/003-534.pdf
Fujikura Europe – How to clean your fusion splicer — https://www.europe.fujikura.com/insights/how-to-clean-your-fusion-splicer/
Fujikura – Limpieza de cleaver CT50 — https://www.optic-product.fujikura.com/support-resources_services/fusion-splicer-maintenance/how-to-clean-the-clamp-pad-anvil-and-cleaver-blade-of-ct50/
Fujikura – Limpieza de guías V y mordazas — https://www.optic-product.fujikura.com/support-resources_services/fusion-splicer-maintenance/how-to-clean-vgroove-and-fiber-clamp-chips-of-90s/
ITU-T G.652 – Characteristics of a single-mode optical fibre and cable — https://www.itu.int/rec/T-REC-G.652/en
ITU-T G.651.1 – Characteristics of a 50/125 µm multimode graded index optical fibre cable — https://www.itu.int/rec/T-REC-G.651.1/en

\---

**Cierre (づ｡◕‿◕｡)づ**  
Un buen empalme no depende de memorizar números universales: depende de identificar la fibra, seleccionar el programa correcto, preparar extremos limpios y bien cortados, seguir el fabricante y verificar el resultado.
