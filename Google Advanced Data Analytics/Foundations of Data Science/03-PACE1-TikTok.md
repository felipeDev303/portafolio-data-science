# PACE

## Instrucciones

Utilice este documento de estrategia PACE para registrar decisiones y reflexiones a medida que trabaja en este proyecto de fin de curso. Puede usarlo como guía para considerar sus respuestas y reflexiones en las diferentes etapas del proceso de análisis de datos. Además, los documentos de estrategia PACE pueden servir como recurso para proyectos futuros.

## Preguntas relevantes para la entrevista

Completar el proyecto de fin de curso te ayudará a responder este tipo de preguntas que suelen formularse durante el proceso de entrevista:

### Describe los pasos que seguirías para limpiar y transformar un conjunto de datos no estructurados.

- Definir objetivo y métricas de calidad de datos.
- Normalizar formatos (fechas, texto en minúsculas, codificación UTF-8).
- Remover/etiquetar duplicados y filas vacías.
- Manejar valores faltantes (eliminar, imputar o marcar) según relevancia.
- Estandarizar categorías y corregir errores tipográficos.
- Tokenizar y limpiar texto (stopwords, signos, emojis) si aplica.
- Detectar y recodificar tipos de datos correctos.
- Crear variables derivadas útiles (longitud de texto, ratios, banderas de verificación, etc.).
- Validar consistencia (rangos plausibles, relaciones entre columnas).

### ¿Qué cosas específicas podría buscar como parte de su proceso de limpieza?

- Duplicados exactos o casi duplicados.
- Tipos incorrectos (números como texto, fechas mal parseadas).
- Categorías inconsistentes (“Verificado”, “verificado”, “No_Verificado”).
- Valores faltantes en columnas clave (target o IDs).
- Texto con ruido (HTML, emojis irrelevantes, URLs).
- Codificación irregular (caracteres rotos).

### ¿Cuáles son algunos de los valores atípicos, anomalías o cosas inusuales que podría buscar en el proceso de limpieza de datos que podrían afectar los análisis o la capacidad de crear información?

- Valores extremos en métricas de video (reproducciones, likes, shares) fuera de un rango razonable.
- Duraciones de video de 0 s o negativas; duraciones excesivamente grandes.
- Conteos de interacciones no enteros o negativos.
- Transcripciones vacías o extremadamente largas.
- Estados imposibles (autor “baneado” con verificación “verificado”).
- Inconsistencias entre métricas (descargas > visualizaciones, comentarios negativos).
- IDs duplicados para distintos registros.

## Guía de referencia

Este proyecto tiene tres tareas; la siguiente imagen identifica cómo se incorporan las etapas de PACE en esas tareas.

Task 1 - Frame the promblem: En esta tarea, enmarcarás el problema y comprenderás los datos que se te han proporcionado. Esto se relaciona con la etapa de PACE de "Enmarcar el problema".

Task 2 - Build dataframe: En esta tarea, inspeccionarás y organizarás los datos. Esto se relaciona con la etapa de PACE de "Construir el marco de datos".

Task 3 - Understand the data: En esta tarea, comprenderás los datos y comunicarás tus hallazgos. Esto se relaciona con la etapa de PACE de "Entender los datos" y "Comunicar los hallazgos".

## Preguntas y consideraciones sobre proyectos de datos

### PACE: Plan Stage

¿Cómo puede usted prepararse mejor para comprender y organizar la información proporcionada?

- Clarificar objetivo y métricas de éxito con stakeholders.
- Mapear fuentes y esquemas de datos; validar diccionarios y supuestos de negocio.
- Definir plan de control de versiones, naming y estructura de carpetas/tableros.

¿Qué libros de códigos de seguimiento y autoevaluación le ayudarán a realizar este trabajo?

- Checklist de calidad de datos (tipos, rangos, duplicados, nulos).
- Guía de estilo de código/notebooks y convenciones de variables.
- Lista de validaciones de consistencia entre tablas (claves, integridad referencial).
- Plantilla de bitácora de experimentos (fecha, cambio, métrica, resultado).

¿Qué actividades adicionales realizaría un estudiante ingenioso antes de comenzar a codificar?

- Hacer un data sketch: columnas clave, relaciones, cardinalidades esperadas.
- Crear preguntas de negocio y métricas derivadas que se necesitarán.
- Prototipar queries simples para evaluar volumen y calidad.
- Establecer entorno reproducible (requirements, env, seeds) y pruebas rápidas de ingestión.

### PACE: Analyze Stage

- ¿La información disponible será suficiente para lograr el objetivo según tu intuición y el análisis de las variables?

- ¿Cómo crearías estadísticas de marcos de datos resumidos y evaluarías el rango mínimo y máximo de los datos?

- ¿Los promedios de alguna de las variables de datos parecen inusuales? ¿Puedes describir los datos del intervalo?

### PACE: Construct Stage

Nota: La etapa de Construcción no se aplica a este flujo de trabajo. El marco PACE se puede adaptar a los requisitos específicos de cada proyecto.

### PACE: Execute Stage

- Dado su conocimiento actual de los datos, ¿qué recomendaría inicialmente a su gerente que investigara más a fondo antes de realizar un análisis exploratorio de datos?

- ¿Qué datos se presentan inicialmente como que contienen anomalías?

- ¿Qué tipos de datos adicionales podrían fortalecer este conjunto de datos?
