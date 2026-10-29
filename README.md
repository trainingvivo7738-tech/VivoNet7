# VivoNet — versión 111

Paquete completo de VivoNet basado en el HTML aprobado por separado.

## Archivos principales
- `index.html`: entrada principal de la aplicación; coincide exactamente con `VivoNet_v44_original.html` y con el HTML aprobado.
- `VivoNet_v44_original.html`: alias compatible con el nombre utilizado en paquetes anteriores; no contiene una versión antigua.
- `vigo.html`: asistente Vigo.
- `manifest.webmanifest`, `service-worker.js` e iconos: instalación PWA, caché y recursos visuales.

## Cambios que contiene el HTML
- Separación solicitada de 12 px entre secciones.
- Separación de 26 px antes de los botones inferiores.
- La tarjeta «¿Sabías que…?» no muestra la flecha rosa y cambia curiosidad/consejo al tocarla; también acepta Enter y barra espaciadora.

## Actualización de caché
El service worker usa la caché `vivonet-v111` para no reutilizar la caché de una versión anterior al actualizar la aplicación instalada.

## Publicación
Extrae todos los archivos y publica su contenido completo en la raíz de tu sitio. Después de actualizar una instalación existente, abre la página con conexión para que se active la nueva caché.
