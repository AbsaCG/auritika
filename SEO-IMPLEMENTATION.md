# Pendientes SEO antes de publicar

1. Publica esta carpeta en un dominio HTTPS definitivo.
2. Añade una etiqueta canonical en `index.html` con la URL exacta del dominio, por ejemplo: `<link rel="canonical" href="https://www.tudominio.pe/">`.
3. Añade las propiedades `og:url` y `twitter:url` con esa misma URL.
4. Crea un `sitemap.xml` con la URL definitiva y añade su ruta al final de `robots.txt` con `Sitemap: https://www.tudominio.pe/sitemap.xml`.
5. Registra el dominio en Google Search Console y envía el sitemap.
6. Sustituye la imagen social de Unsplash por una foto propia de 1200 × 630 px alojada en el dominio. Actualiza `og:image` y `twitter:image`.
7. Reemplaza `WHATSAPP_NUMBER` en `main.js` y, cuando estén disponibles, agrega número telefónico y dirección comercial verificable al marcado estructurado.

No se añadió una URL canónica ficticia: una canonical incorrecta puede perjudicar la indexación.
