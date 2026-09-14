# Cómo piensa un analista de datos

Demo interactivo para webinar. Recorre el caso de Netflix —por qué te muestra
justo eso— y aterriza el mismo método en psicología, salud, ingeniería y
negocio. Sin código y sin fórmulas.

**Ver:** https://hesusg.github.io/como-piensa-un-analista/

## Dos modos

| Liga | Para qué |
|---|---|
| `/` | Scroll libre. Es la que se comparte con los asistentes; funciona en celular. |
| `/?modo=presentar` | Escenas una por una. Avanza con `→`, espacio o clicker. Es la que se proyecta. |

Extra: `?esc=8` abre directo en esa escena, útil para ensayar una parte suelta.

## Cómo está hecho

Un solo archivo `index.html`, sin build y sin dependencias — nada que se pueda
caer a media presentación. El SVG está escrito a mano y las capas se encienden
por escena; todo el renderizado lo hace CSS a partir de un atributo en la raíz.

Las fuentes de los datos están en el apéndice del propio sitio.
