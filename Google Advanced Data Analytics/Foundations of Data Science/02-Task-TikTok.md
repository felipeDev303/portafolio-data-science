# Task Actividad 1

## Resumen de la actividad

En esta actividad, completarás un proyecto que demuestra tu capacidad para usar Python para importar, inspeccionar y organizar datos. También informarás a los miembros del equipo mediante un resumen ejecutivo, demostrando tu capacidad para organizar y comunicar información clave.

Ya habías aprendido sobre una herramienta que puede ayudarte a completar la planificación y desarrollo de proyectos: el documento de estrategia PACE. Utilizarás el documento de estrategia PACE para guiarte durante el proceso de inspección y organización de tus datos.

Asegúrate de completar esta actividad antes de continuar. El siguiente punto del curso te proporcionará ejemplos completados para comparar con tu propio trabajo. No podrás acceder a los ejemplares hasta que hayas completado esta actividad.

## Escenario

TikTok, uno de los principales destinos mundiales para vídeos móviles de formato corto, acaba de contratarte como el nuevo miembro de su equipo de análisis de datos. En un correo anterior, tu supervisor compartió algunos puntos clave de la última reunión del equipo directivo de TikTok. También revisaste una propuesta de proyecto para el nuevo proyecto de clasificación de reclamaciones.

Tu equipo aún está en las primeras fases de su proyecto para desarrollar un modelo de aprendizaje automático que clasifice las reclamaciones en vídeos.

Has recibido la notificación de que tu equipo ha recibido acceso a los datos de usuarios de TikTok. Para obtener información clara, los datos deben ser inspeccionados, organizados y preparados para su análisis.

Descubres dos nuevos correos electrónicos en tu bandeja de entrada: uno de tu supervisora, Rosie Mae Bradshaw, y otro de Willow Jaffey, la responsable de Ciencia de Datos del equipo de datos. Revisa los correos electrónicos y luego sigue las instrucciones proporcionadas para completar el documento de estrategia PACE, el cuaderno de códigos y el resumen ejecutivo.

Nota: Los nombres de los miembros del equipo usados en este escenario laboral son ficticios y no representan TikTok.

---

Correo electrónico de Rosie Mae Bradshaw, Responsable de Ciencia de Datos

Asunto: ¿Ayuda con el cuaderno de programación?

De: "Bradshaw, Rosie Mae" —rosiemaebradshaw@tiktok

Cc: "Rainier, Orion"—orionrainier@tiktok

Buenos días,

Tengo una actualización sobre el proyecto de clasificación de reclamaciones. Acabo de recibir un correo electrónico de nuestra responsable de gestión de proyectos, Mary Joanna Rodgers, informando que el equipo de datos está autorizado a continuar.

Antes de comenzar el proceso de Análisis Exploratorio de Datos (EDA), realmente necesitamos tu ayuda con la codificación y preparación de los datos. Durante tu entrevista mencionaste que trabajaste con Python en el programa de certificación de Google que completaste. Esa experiencia suena aplicable aquí.

Orion Rainier (copiado arriba) inició un cuaderno Jupyter con el conjunto de datos correspondiente (adjunto). Orion está muy involucrado en las etapas finales de otro proyecto. Estoy seguro de que agradecería mucho tu ayuda para completar la programación y preparar el cuaderno para el proyecto.

Orion, ¿te importaría compartir los detalles?

Con los más humildes cordiales,

Rosie Mae Bradshaw

Gestor de Ciencia de Datos

TikTok

---

Correo electrónico de Orion Rainier, científico de datos

Asunto: RE: ¿Ayuda con el cuaderno de programación?

De: "Rainier, Orion"—orionrainier@tiktok

Cc: "Bradshaw, Rosie Mae" —rosiemaebradshaw@tiktok

¡Encantado de conocerte (virtualmente)!

¡Espero que hayas disfrutado tus primeras semanas!

La propuesta de proyecto que revisaste cubrió los puntos principales de este proyecto, así que te daré más contexto y compartiré cómo puedes ayudar al equipo.

El objetivo de este proyecto es construir un modelo de aprendizaje automático que pueda agilizar el proceso de reclamaciones identificando si las declaraciones hechas en vídeos son afirmaciones u opiniones.

Una afirmación se refiere a información que no tiene fuentes o proviene de una fuente no verificada. Por ejemplo, "Las noticias informaron que alguien reveló que alrededor del 50% del oro extraído en la Tierra proviene de una sola fuente."

Las opiniones se refieren a las creencias o pensamientos personales de un grupo o individuo. Aquí tienes un ejemplo: "En mi opinión, el día laboral más productivo de la semana es el martes."

Ahora, estamos listos para comenzar el proceso de preparación de los datos de clasificación de reclamaciones para su análisis. Hay varios miembros del equipo de datos comprometidos en ajustar el aprendizaje automático desarrollado para el último proyecto, ¡así que tu ayuda para preparar los datos es muy apreciada!

Hasta que terminemos el proyecto anterior, no es necesario hacer una EDA completa sobre estos datos. Ya llegaremos a eso pronto. ¿Te importaría importar los datos (adjuntos) y revisarlos para el equipo? Sería fantástico si pudieras incluir un resumen de la columna Tipos de datos, valores de datos, conteos no nulos, columnas relevantes e irrelevantes, junto con cualquier otra cosa relacionada con el código que creas que merece la pena compartir o mostrar en el cuaderno. Tendrás que seleccionar un par de variables en las que centrarte. Incluye sus valores mínimos y máximos. Aún no he analizado los datos detenidamente, pero sería muy útil si pudieras crear variables significativas combinando o modificando las estructuras que se ofrecen.

Gracias,

Orion Rainier

Científico de datos

TikTok

–

"El big data no va de bits, es de talento." — Douglas Merrill

---

## 📋 Recursos y Próximos Pasos

### Documentos a completar:

**1. Documento de Estrategia PACE (Curso 1)**

- Responder preguntas sobre Plan, Analyze, Construct, Execute
- Documentar decisiones para cada fase

**2. Laboratorio de Proyecto de TikTok (Jupyter Notebook)**

- Importar e inspeccionar datos
- Organizar datos para análisis exploratorio
- Escribir código comentado

**3. Resumen Ejecutivo (Curso 1)**

- Resumen de tareas completadas
- Resultados del análisis de variables
- Recomendaciones para siguiente fase (modelado predictivo)

### Task del proyecto del curso:

Independientemente del camino que hayas elegido completar, tus objetivos para este proyecto son:

- [ ] Complete las preguntas del documento de estrategia PACE del Curso 1
- [ ] Responda las preguntas en el archivo del proyecto del cuaderno Jupyter
- [ ] Completar el trabajo de preparación de codificación en el cuaderno Jupyter del proyecto
- [ ] Resumir los tipos de columna
- [ ] Comunicar hallazgos importantes en forma de resumen ejecutivo

---

## 🔍 Tareas de Análisis Inicial

Rosie Mae solicita que completes las siguientes tareas de análisis:

### Tareas Prioritarias:

1. **Importar y revisar los datos** para el equipo
2. **Generar resumen de tipos de datos** (dtypes)
3. **Análisis de valores faltantes** (conteo de registros no nulos)
4. **Evaluación de relevancia de variables** (columnas útiles vs irrelevantes)
5. **Creación de variables derivadas** (combinación de estructuras existentes)
6. **Análisis de variables clave** (mínimos, máximos y distribuciones)

### Componentes del Análisis:

- 📥 **Importación de datos**
- 🔧 **Carga de paquetes necesarios** (pandas, numpy, matplotlib, seaborn)
- 🏗️ **Identificación de estructuras de datos** y análisis descriptivo
- 🔎 **Extracción de información por columna**
- 🔀 **Transformación de datos** para crear variables significativas
