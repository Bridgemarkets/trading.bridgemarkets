# trading.bridgemarkets

Página estática de Bridge Markets en HTML y CSS vanilla, sin dependencias ni compilación.

## Abrir

Abre `index.html` directamente en el navegador.

## Versiones

- Móvil (hasta 767 px): `assets/mobile.webp`, imagen original de historia 1080 × 1920, centrada con un ancho máximo de 320 px.
- Escritorio (desde 768 px): `assets/desktop.jpg`, imagen original de feed 1080 × 1350, centrada y ajustada a la altura de la ventana.
- Las imágenes mantienen sus proporciones y se muestran completas, sin recortes. En móvil se puede desplazar la página si hace falta.
- Toda la imagen es un enlace a `https://clients.bridgemarkets.global/`, en la misma pestaña. También funciona con Tab y Enter.
- Fondo con degradado lavanda y violeta, y borde animado con velocidades variables. La animación respeta la preferencia de movimiento reducido del dispositivo.

No se necesita JavaScript para seleccionar la imagen ni para navegar: se usan `<picture>` y un enlace HTML nativo.

## Publicar

Copia el contenido completo de esta carpeta a cualquier alojamiento estático, conservando la carpeta `assets` junto a `index.html` y `styles.css`.
