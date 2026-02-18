# TikTok: Proyecto de Clasificación de Reclamaciones

## Resumen de Portafolio - Curso 1

---

## 📋 Tabla de Contenidos

- [Resumen Ejecutivo](#resumen-ejecutivo)
- [Contexto del Escenario](#contexto-sobre-el-escenario-de-tiktok)
- [Antecedentes del Proyecto](#antecedentes-del-proyecto)
- [Tu Asignación](#tu-asignación)
- [Equipo de TikTok](#miembros-del-equipo-en-tiktok)
- [Notas de la Reunión](#notas-de-la-reunión)
- [Metodología PACE](#pace)
- [Diccionario de Datos](#diccionario-de-datos)
- [Entregables del Proyecto](#entregables-específicos-del-proyecto)

---

## 🎯 Resumen Ejecutivo

Este proyecto busca desarrollar un **modelo predictivo de clasificación** que distinga automáticamente entre **afirmaciones** y **opiniones** en el contenido de videos de TikTok. El objetivo es reducir el atraso en la revisión de reportes de moderación y priorizar el contenido de manera más eficiente.

**Duración estimada:** 8-9 semanas  
**Entrega final:** Modelo de machine learning con métricas de desempeño validadas

---

## Contexto sobre el escenario de TikTok

¡Bienvenido a tu nuevo puesto en TikTok! ¡Estamos encantados de tenerte en el equipo de datos!

En TikTok, nuestra misión es inspirar la creatividad y traer alegría. Nuestros empleados lideran con curiosidad y se mueven a la velocidad de la cultura. Combinado con la estructura plana de nuestra empresa, se te ofrecerán oportunidades dinámicas para tener un impacto real en una empresa en rápido crecimiento y hacer crecer tu carrera.

Los usuarios de TikTok tienen la capacidad de denunciar vídeos y comentarios que contengan afirmaciones de usuarios. Estos informes identifican el contenido que debe ser revisado por los moderadores. Este proceso genera un gran número de informes de usuarios que son difíciles de abordar rápidamente.

TikTok está trabajando en el desarrollo de un modelo predictivo que puede determinar si un vídeo contiene una afirmación o ofrece una opinión. Con un modelo de predicción exitoso, TikTok puede reducir el atraso en los informes de usuarios y priorizarlos de forma más eficiente.

### Antecedentes del proyecto

El equipo de datos de TikTok se encuentra en las primeras fases del proyecto de clasificación de reclamaciones. El equipo de datos ha creado una propuesta de proyecto para organizar las tareas en hitos, hacer seguimiento de los entregables clave e identificar los interesados relevantes. La propuesta clasifica las tareas utilizando el flujo de trabajo PACE que conociste antes. Revisa la propuesta para familiarizarte con el proyecto antes de empezar a trabajar en tu primera tarea.

Para acceder a este elemento del curso acceder a la plantilla de propuesta de proyecto y al laboratorio de proyecto de final de curso.

Se requieren las siguientes tareas antes de que el equipo pueda comenzar el proceso de análisis de datos:

- Crea un dataframe para el conjunto de datos de TikTok
- Examina el tipo de datos de cada columna
- Recopila estadísticas descriptivas

### Tu asignación

Para tu primera tarea, construirás un marco de datos para los datos de clasificación de reclamaciones. Una vez completado el dataframe, organizarás los datos de reclamaciones para el proceso de análisis exploratorio de datos y actualizarás al equipo sobre tu progreso y conocimientos.

---

## 👥 Miembros del Equipo en TikTok

Como analista de datos nuevo, trabajarás estrechamente con un equipo talentoso de profesionales experimentados. A continuación se presenta la estructura del equipo:

### Equipo de Datos

| Nombre             | Rol                             | Área de Especialidad             |
| ------------------ | ------------------------------- | -------------------------------- |
| Willow Jaffey      | Responsable de Ciencia de Datos | Modelado predictivo y evaluación |
| Rosie Mae Bradshaw | Responsable de Ciencia de Datos | Supervisión general del proyecto |
| Orion Rainier      | Científico de Datos             | Análisis exploratorio de datos   |

**Pauta de comunicación:** Los equipos técnicos apprecian mensajes concisos y específicos.

### Equipo Multifuncional

| Nombre              | Rol                                 | Responsabilidad                     |
| ------------------- | ----------------------------------- | ----------------------------------- |
| Mary Joanna Rodgers | Responsable de Gestión de Proyectos | Coordinación de hitos y entregables |
| Margery Adebowale   | Responsable de Finanzas, América    | Presupuesto y recursos              |
| Maika Abadi         | Responsable de Operaciones          | Logística operacional               |

**Pauta de comunicación:** Adapta tu lenguaje a roles menos técnicos, enfocándote en resultados y impacto.

---

## 📧 Notas de la Reunión

### Email de Rosie Mae Bradshaw

> **De:** Rosie Mae Bradshaw, Responsable de Ciencia de Datos  
> **Asunto:** Tu primera tarea: Revisar las notas de la reunión

¡Bienvenido al equipo! A continuación encontrarás un extracto de mis notas de la reunión interna con el equipo directivo sobre el proyecto de clasificación de reclamaciones.

---

### 📝 Resumen por Stakeholder

#### 1️⃣ Mary Joanna Rodgers | Gestión de Proyectos

- ✅ Documento de proyecto a nivel global creado (identifica entregables y hitos)
- 📊 **Necesidad:** Generar visualizaciones para compartir con ejecutivos de TikTok

#### 2️⃣ Orion Rainier | Científico de Datos

- 📚 Necesidad de comprensión profunda de los datos
- 🔍 Inspección de datos faltantes
- 📉 Análisis Exploratorio de Datos (EDA) para identificar información útil
- 📈 Aplicación de métodos de pruebas estadísticas

#### 3️⃣ Willow Jaffey | Responsable de Ciencia de Datos

- 🎯 Objetivo principal: **Entregar un modelo confiable de machine learning**
- 🔧 Determinar el tipo de modelo de regresión apropiado
- 💬 Puntos clave de conversación para presentación ejecutiva
- ⚙️ Seleccionar el mejor método de prueba de hipótesis

#### 4️⃣ Perspectivas de Rosie Mae Bradshaw

- 🐍 **Tecnología recomendada:** Python para el desarrollo
- ✓ Revisar supuestos de cualquier modelo de regresión desarrollado

---

### 💡 Contexto del Proyecto

**Objetivo central:** Desarrollar un modelo de aprendizaje automático que distinga entre **afirmaciones** y **opiniones** en el contenido de TikTok.

**Definiciones clave:**

- **Afirmación:** Información sin fuentes verificadas (ej: "Las noticias informaron que alrededor del 50% del oro extraído proviene de una sola fuente")
- **Opinión:** Creencias o pensamientos personales (ej: "En mi opinión, el martes es el día laboral más productivo")

**Motivación:** La escala de publicaciones e interacciones en TikTok hace imposible que los moderadores revisen todo manualmente. Este modelo priorizará contenido para revisión más eficiente.

---

### 🎉 Nota Personal

> No olvides el almuerzo patrocinado por la empresa el viernes. ¡Excelente oportunidad para conocer colegas! El equipo se reúne en el vestíbulo alrededor del mediodía.

---

## 🎯 Entregables Específicos del Proyecto

En este proyecto de final de curso, obtendrás experiencia práctica en un flujo de trabajo de ciencia de datos completo. Estos son tus entregables clave:

| #   | Entregable                   | Descripción                                              |
| --- | ---------------------------- | -------------------------------------------------------- |
| 1   | 📋 Documento PACE            | Responder preguntas de estrategia PACE para cada fase    |
| 2   | 💻 Notebook Jupyter          | Código completo de preparación y análisis de datos       |
| 3   | 📊 Resumen de Tipos de Datos | Documentar dtypes y estructura del dataset               |
| 4   | 📈 Resumen Ejecutivo         | Presentar hallazgos principales en forma clara y concisa |

**Tareas técnicas:**

- Importación y carga de datos
- Investigación de estructuras de datos
- Creación de variables significativas
- Identificación de columnas relevantes vs irrelevantes

---

## 🔄 PACE: Estructura del Proyecto

### **Hito 1** | Plan (1-2 días)

**Objetivo:** Establecer la estructura y alcance del proyecto

- Entregable: Documento de proyecto a nivel global
- Actividad: Escribir propuesta formal del proyecto

---

### **Hito 2** | Analyze (2-3 semanas)

**Objetivo:** Recopilar y preparar datos para exploración

- Entregable: Archivos de datos listos para EDA
- Actividad: Iniciar exploración de datos

---

### **Hito 3** | Analyze & Construct (1 semana)

**Objetivo:** Exploración visual y limpieza de datos

- Entregable: Resultados de Análisis Exploratorio de Datos (EDA)
- Entregable adicional: Visualizaciones y dashboard de Tableau

---

### **Hito 4** | Analyze & Construct (1 semana)

**Objetivo:** Análisis estadístico profundo

- Entregable: Análisis de estadísticas descriptivas
- Entregable adicional: Resultados de pruebas de hipótesis

---

### **Hito 5** | Analyze & Execute (1-2 semanas)

**Objetivo:** Desarrollo inicial de modelo de regresión

- Tarea: Construir modelo de regresión lineal
- Tarea: Evaluar desempeño del modelo

---

### **Hito 6** | Construct & Execute (2 semanas)

**Objetivo:** Construcción de modelo final y presentación

- Entregable: Modelo de machine learning calibrado
- Entregable final: Presentación ejecutiva para stakeholders
- Actividad: Comunicar perspectivas principales
