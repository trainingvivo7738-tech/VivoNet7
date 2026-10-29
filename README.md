# VivoNet — versión 44

Aplicación web estática para herramientas de apoyo a promotores vivo. Esta carpeta está preparada para publicarse en GitHub Pages.

## Contenido
- `index.html`: aplicación basada en VivoNet v44, conservada como punto de partida.
- `manifest.webmanifest`: configuración PWA con nombre, colores e iconos.
- `icons/`: icono oficial aprobado de VivoNet en PNG y una versión SVG editable del símbolo.

## Publicar con GitHub Pages
1. Sube todos los archivos y la carpeta `icons` a la raíz de tu repositorio.
2. En GitHub, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Selecciona la rama principal (normalmente `main`) y la carpeta `/ (root)`, y guarda.
5. Espera a que GitHub Pages muestre la URL publicada.

## Instalar como aplicación
Abre la URL HTTPS publicada en el navegador del teléfono y usa la opción del navegador para añadirla a la pantalla de inicio. La disponibilidad del modo instalable depende del navegador y de que el sitio esté publicado por HTTPS.

## Icono oficial
El icono principal aprobado es `vivonet-icon-1024.png`. Los PNG de tamaños menores están optimizados para navegador, Android y acceso directo. `icons/icon.svg` es una versión vectorial simplificada y editable del símbolo.


El paquete incluye `service-worker.js` para habilitar instalación PWA y soporte básico sin conexión. Los íconos están en la raíz del repositorio para facilitar la carga desde el navegador móvil.


Actualización: VivoNet v44 incluye 20 curiosidades con recomendaciones prácticas para la venta.


## Vigo integrado (v76)
Se agregó la tarjeta **Vigo** a las herramientas principales. Abre `vigo.html` y el botón «Regresar a VivoNet» vuelve a la pantalla principal. La página de Vigo se incluye en la caché del service worker.


## VivoNet v107
- Separación entre secciones ajustada a 12 px.
- Separación antes de los botones inferiores ajustada a 26 px.
- Eliminada la flecha rosa; al tocar la tarjeta de curiosidad cambia el dato y el consejo.
