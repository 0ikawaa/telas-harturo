# Telas Harturo

Catálogo online de telas de tapicería de **Harturo Tapicería** (Montevideo).

Sitio estático: un solo `index.html` sin dependencias ni build. Se publica tal cual.

## Contenido

20 telas, cada una con dos fotos: la textura en detalle y la carta de colores completa.
Las imágenes salen del catálogo original de Canva, extraídas en su resolución nativa y
convertidas a WebP en tres tamaños:

| sufijo | ancho | para qué |
|---|---|---|
| `-tira` | 220 px | tira en movimiento de la portada y navegación de la ficha |
| `-thumb` | 700 px | grilla y foto grande de la portada |
| `-color` | 700 px | carta de colores al pasar el mouse en la grilla |
| `-textura` / `-carta` | 950 px | ficha a pantalla completa |

`titulo.webp` es el tejido Dracco, que rellena las letras del título.

## Editar el catálogo

Las telas están en el array `TELAS` dentro de `index.html`. Cada entrada necesita su
`slug`, `nombre` y `desc`, más las imágenes correspondientes en `img/`.

## Contacto del negocio

099 005 220 · [@tapiceriaharturo](https://www.instagram.com/tapiceriaharturo/)
