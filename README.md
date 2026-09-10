# Juanma Rodriguez Prod

Landing page / portfolio de Juanma Rodriguez, productor musical e ingeniero de sonido en Sant Joan Despí (Barcelona).

Sitio estático: un solo `index.html` con CSS y JS integrados, sin build ni backend.

- `index.html` — la web completa. Todo el contenido variable está en el bloque `CONFIG` al inicio del script.
- `assets/img/` — imágenes optimizadas en WebP con fallback JPEG, favicons e imagen Open Graph.
- `assets/covers/` — portadas de Spotify en JPEG (fallback).
- `_headers` — cabeceras para Cloudflare Pages. En Vercel se ignora.
- `robots.txt`, `sitemap.xml` — SEO.

Integraciones sin servidor: Booksy (widget oficial), WhatsApp click-to-chat, Spotify (previews oficiales + iFrame API), Google Maps embed.
