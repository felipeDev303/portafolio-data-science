# 📊 Diccionario de Datos

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
