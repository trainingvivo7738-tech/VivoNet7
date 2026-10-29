# VivoNet — versión 110

Proyecto web estático de VivoNet preparado para publicación en GitHub Pages y uso como aplicación web progresiva (PWA).

## Archivos principales
- `index.html`: pantalla principal de VivoNet con los ajustes de espaciado y la tarjeta de curiosidad interactiva.
- `vigo.html`: página del asistente Vigo.
- `manifest.webmanifest` y `service-worker.js`: instalación PWA y actualización de caché.
- Iconos PNG y SVG usados por el navegador y el acceso directo.

## Cambios incluidos
- Separación entre secciones: 12 px.
- Separación antes de los botones inferiores: 26 px.
- Eliminada la flecha rosa de «¿Sabías que…?». Al tocar la tarjeta se cambia la curiosidad y el consejo de venta; admite Enter y barra espaciadora.
- Caché PWA versionada como `vivonet-v110` para evitar mantener la versión anterior almacenada.

## Publicar
Sube el contenido de esta carpeta a la raíz del repositorio y publica la rama principal en GitHub Pages. Después de actualizar una instalación existente, abre la página con conexión para permitir que el service worker descargue la nueva versión.
