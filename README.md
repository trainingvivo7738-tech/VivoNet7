# VivoNet — paquete reconstruido v120

Este ZIP se reconstruyó usando como fuente única el HTML aprobado `VivoNet_v119_vigo_mas_compacto.html`.

## Archivos principales
- `index.html`: aplicación principal; coincide byte por byte con el HTML de referencia entregado.
- `VivoNet_v44_original.html`: alias histórico; es idéntico a `index.html` y no es una versión antigua.
- `vigo.html`: Vigo independiente; coincide exactamente con el payload de Vigo integrado dentro de `index.html`.
- `service-worker.js`: caché `vivonet-v120` para forzar la renovación de recursos al publicar el paquete.
- `manifest.webmanifest`, iconos y `.nojekyll`: recursos de publicación e instalación.

## Espaciado aprobado en el HTML
- Espacios generales: 9 px.
- Entre las secciones y los accesos inferiores: 14 px.
- Tarjeta de Vigo: versión compacta aprobada (v119), sin cambios visuales adicionales en esta reconstrucción.

## Publicación
Extrae todos los archivos y publica el contenido completo en la raíz del sitio. Al actualizar una instalación previa, abre el sitio con conexión y cierra las pestañas antiguas para que el service worker nuevo pueda activarse.
