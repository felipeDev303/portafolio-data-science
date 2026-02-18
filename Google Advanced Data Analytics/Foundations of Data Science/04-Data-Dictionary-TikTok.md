# 📊 Diccionario de Datos

Este proyecto utiliza un conjunto de datos llamado tiktok_dataset.csv. Contiene datos sintéticos creados para este proyecto en colaboración con TikTok.

El conjunto de datos contiene

19.383 filas - Cada fila representa un vídeo de TikTok diferente publicado en el que se ha hecho una afirmación/opinión.

12 columnas

El conjunto de datos contiene información sobre videos de TikTok que han sido etiquetados como afirmaciones u opiniones. A continuación se describe cada variable:

| Columna                    | Tipo  | Descripción                                                                                                                                                                                                                                                                                                |
| -------------------------- | ----- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `#`                        | int   | Número asignado por TikTok al vídeo con reclamación/opinión.                                                                                                                                                                                                                                               |
| `claim_status`             | obj   | Si el vídeo publicado ha sido identificado como una "opinión" o una "reivindicación" En este conjunto de datos, una "opinión" se refiere a la creencia o pensamiento personal de un individuo o grupo. Una "afirmación" se refiere a una información sin fuentes o procedente de una fuente no verificada. |
| `video_id`                 | int   | Número de identificación aleatorio asignado al vídeo en el momento de su publicación en TikTok.publicado                                                                                                                                                                                                   |
| `video_duration_sec`       | int   | Duración del video en segundos                                                                                                                                                                                                                                                                             |
| `video_transcription_text` | obj   | Transcripción del contenido de audio del video                                                                                                                                                                                                                                                             |
| `verified_status`          | obj   | Indica el estado del usuario de TikTok que publicó el video en términos de su verificación, ya sea "verificado" o "no verificado"                                                                                                                                                                          |
| `author_ban_status`        | obj   | Indica el estado del usuario de TikTok que publicó el vídeo en cuanto a sus permisos: "activo", "bajo verificación" o "baneado".                                                                                                                                                                           |
| `video_view_count`         | float | Total de reproducciones del video                                                                                                                                                                                                                                                                          |
| `video_like_count`         | float | Total de me gusta recibidos                                                                                                                                                                                                                                                                                |
| `video_share_count`        | float | Total de veces compartido                                                                                                                                                                                                                                                                                  |
| `video_download_count`     | float | Total de descargas                                                                                                                                                                                                                                                                                         |
| `video_comment_count`      | float | Total de comentarios                                                                                                                                                                                                                                                                                       |

---

## Acceda al laboratorio del proyecto de fin de curso

Archivos del laboratorio del proyecto de fin de curso disponibles en la carpeta [Files](../Foundations%20of%20Data%20Science/Files/).

Nota: Haga clic en el botón Abrir laboratorio para iniciar el laboratorio del proyecto de fin de curso. Una vez que haya completado esta actividad, haga clic en Siguiente para continuar con la lectura del ejemplo.

**Instrucciones de la actividad (de laboratorio):**

El Jupyter Notebook se guardará automáticamente a medida que trabajes, o puedes guardarlo manualmente haciendo clic en el botón Guardar y comprobar o seleccionando Guardar y comprobar en el menú Archivo .

A medida que complete el laboratorio del proyecto de fin de curso, tenga en cuenta las siguientes características:

Secciones: Las instrucciones paso a paso de cada sección le guiarán a través del laboratorio.

Bloques de código: Los bloques de código le permiten practicar conceptos clave de codificación en Python. Añada código donde se le pida y haga clic en el botón Ejecutar para ejecutar el código y ver los posibles resultados.

Preguntas: Las preguntas de reflexión ofrecen momentos para detenerse y pensar sobre los conceptos y sus resultados a medida que avanza por el laboratorio.
