# CAT Reflectiva Punta de Seguridad

Landing de un solo producto (misma base que cat-campero y velez-thomas). Precio $179.900 (antes $299.900, -40%), tallas 37 a 44.

## Colores: Negra, Oro, Gris, Azul, Café

## Galería por color: 5 fotos + 1 video al final
- Fotos (carpeta `img/`, jpg): `reflectiva-punta-<color>-0.jpg` … `-4.jpg`, con color = `negra`, `oro`, `gris`, `azul`, `cafe`. La `-0` es la portada (vista 3/4 del par); `-1` perfil, `-2` perfil opuesto, `-3` detalle del logo, `-4` suela.
- Video (carpeta `video/`, ya incluidos): `CAT-REFLECTIVA-NEGRA.mp4`, `-ORO`, `-GRIS`, `-AZUL`, `-CAFE`. Sin sonido, arrancan solos al llegar a ellos y se repiten en bucle.
- Lo que falte se omite solo.

### Medidas de la galería
Marco vertical **3:4**, ancho completo (520 px máx. en computador, ~375 px en celular). Las imágenes se ajustan en modo "cubrir": lo que sobra se recorta, no se deforma.
- Fotos: **1200 × 1600 px** (3:4), vertical, con la bota en el centro y aire alrededor.
- Videos 9:16: se recorta ~12% arriba y abajo. Mantén la bota en el centro.

Opcional: `img/uso-1..4.jpg` y `video/reflectiva-punta.mp4` (vertical 9:16, sección aparte más abajo).

## Estado
Fotos (5 por color), videos, fotos de uso, Mercado Pago y botón flotante de WhatsApp: listos. WhatsApp: `573224146909`.

## Único pendiente: conectar el píxel de Meta
1. `index.html` (en el `<head>`, bloque "META PIXEL"): cambia `TU_PIXEL_ID_AQUI` por tu ID y quita el `<!--` del inicio y el `-->` del final del bloque. Dispara PageView y, al confirmar el pedido, Lead.
2. `gracias.html` (bloque "META"): igual, cambia `TU_PIXEL_ID_AQUI` por tu ID y descomenta. Dispara Purchase por $179.900.
3. Opcional: bloques de TikTok en los mismos sitios.
