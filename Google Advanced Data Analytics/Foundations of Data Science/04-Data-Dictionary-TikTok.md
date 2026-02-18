# 📊 Diccionario de Datos

Este proyecto utiliza un conjunto de datos llamado tiktok_dataset.csv. Contiene datos sintéticos creados para este proyecto en colaboración con TikTok.

El conjunto de datos contiene

19.383 filas - Cada fila representa un vídeo de TikTok diferente publicado en el que se ha hecho una afirmación/opinión.

12 columnas

El conjunto de datos contiene información sobre videos de TikTok que han sido etiquetados como afirmaciones u opiniones. A continuación se describe cada variable:

| Columna                    | Tipo  | Descripción                                                      |
| -------------------------- | ----- | ---------------------------------------------------------------- |
| `#`                        | int   | ID único del video en el sistema de TikTok                       |
| `claim_status`             | str   | **[TARGET]** Clasificación: "afirmación" u "opinión"             |
| `video_id`                 | int   | Identificador alfanumérico del video publicado                   |
| `video_duration_sec`       | int   | Duración del video en segundos                                   |
| `video_transcription_text` | str   | Transcripción del contenido de audio del video                   |
| `verified_status`          | str   | Estado de verificación del autor: "verificado" o "no verificado" |
| `author_ban_status`        | str   | Estado del autor: "activo", "bajo escrutinio" o "baneado"        |
| `video_view_count`         | float | Total de reproducciones del video                                |
| `video_like_count`         | float | Total de me gusta recibidos                                      |
| `video_share_count`        | float | Total de veces compartido                                        |
| `video_download_count`     | float | Total de descargas                                               |
| `video_comment_count`      | float | Total de comentarios                                             |

---

## Acceda al laboratorio del proyecto de fin de curso

Archivos del laboratorio del proyecto de fin de curso disponibles en la carpeta [Files](../Foundations%20of%20Data%20Science/Files/).

Nota: Haga clic en el botón Abrir laboratorio para iniciar el laboratorio del proyecto de fin de curso. Una vez que haya completado esta actividad, haga clic en Siguiente para continuar con la lectura del ejemplo.

instrucciones de la actividad (de laboratorio):

El Jupyter Notebook se guardará automáticamente a medida que trabajes, o puedes guardarlo manualmente haciendo clic en el botón Guardar y comprobar o seleccionando Guardar y comprobar en el menú Archivo .

A medida que complete el laboratorio del proyecto de fin de curso, tenga en cuenta las siguientes características:

Secciones: Las instrucciones paso a paso de cada sección le guiarán a través del laboratorio.

Bloques de código: Los bloques de código le permiten practicar conceptos clave de codificación en Python. Añada código donde se le pida y haga clic en el botón Ejecutar para ejecutar el código y ver los posibles resultados.

Preguntas: Las preguntas de reflexión ofrecen momentos para detenerse y pensar sobre los conceptos y sus resultados a medida que avanza por el laboratorio.
