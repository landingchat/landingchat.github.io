# LANDINGCHAT

Landing page estática con:

- 1 imagen full viewport
- CTA central: CHAT WITH ME FOR FREE!
- 5 imágenes configurables
- URL independiente por cada imagen
- borde arcoíris animado alrededor del viewport
- panel oculto de configuración
- dummy images reemplazables

## Acceso al panel oculto

Opciones:

1. Abrir la landing con:

   index.html#vault

2. Hacer 5 clicks en la esquina superior izquierda invisible.

3. Atajo:

   CTRL + SHIFT + L

Clave por defecto:

landingchat2026

## Cambiar clave

Editar en index.html:

const ADMIN_PASSCODE = "landingchat2026";

## Reemplazar imágenes

Reemplaza estos archivos:

images/bg-1.svg
images/bg-2.svg
images/bg-3.svg
images/bg-4.svg
images/bg-5.svg

Puedes usar JPG, PNG, WEBP o SVG.

Luego actualiza las rutas en el panel o directamente en DEFAULT_CONFIG.

## Nota importante

Esta versión es estática. El panel guarda configuración en localStorage del navegador.
Para cambios globales publicados, modifica DEFAULT_CONFIG o reemplaza las imágenes en /images y vuelve a subir a GitHub.
