# CauchoPro - Catálogo 2026 (sitio estático)

## Cómo abrir
- Doble clic en `index.html` (abre en tu navegador)

## Dónde están las imágenes del catálogo
- `assets/catalogo/catalogo-pagina-01.png` ... `catalogo-pagina-15.png`

## Editar contacto
En `index.html` busca:
- `https://wa.me/56900000000`
- `ventas@tudominio.cl`
y reemplaza con tus datos.

## Subir a un hosting
Este proyecto es 100% estático (HTML/CSS/JS). Puedes subirlo a:
- Netlify / Vercel / GitHub Pages
- Cualquier hosting tradicional (cPanel), subiendo la carpeta completa.


## Lightbox (visor de imágenes)
- En la sección "Imágenes" puedes navegar con ◀ ▶ o con flechas del teclado.
- También puedes hacer clic en la imagen de un producto para verla en grande.

## Cambiar la imagen de un producto
En `index.html`, en el arreglo `products`, cambia el campo `image:` por la página que corresponda.
Ej: `assets/catalogo/catalogo-pagina-03.png`


## Listo para celular (responsive + WebP)
- Se generaron versiones WebP de las páginas del catálogo para cargar rápido en 4G.
- El sitio es responsive y el lightbox funciona con toque y scroll.

## Publicarlo para que abra en cualquier celular (recomendado: Netlify)
1) Entra a Netlify y crea cuenta.
2) "Add new site" → "Deploy manually".
3) Arrastra la carpeta descomprimida o el ZIP.
4) Te dará una URL pública (https://xxxx.netlify.app) que abre en iPhone/Android.

Si usas tu propio hosting, sube TODOS los archivos y carpetas al directorio público (public_html).

## Nota sobre GitHub Pages (uso comercial)
GitHub indica que Pages no está pensado para alojar un negocio online como hosting gratuito.
Para producción (clientes/ventas) usa Netlify/Vercel o tu hosting con dominio.
