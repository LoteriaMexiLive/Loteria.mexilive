# LOTERÍA MEXILIVE — versión online

Esta versión está preparada para publicarse como aplicación web y abrirse desde cualquier celular mediante un enlace HTTPS.

## Publicación recomendada: Render

1. Sube esta carpeta a un repositorio de GitHub.
2. En Render crea **New → Web Service** y conecta el repositorio.
3. Configura:
   - Runtime: Node
   - Build Command: `npm install`
   - Start Command: `npm start`
4. Render generará una dirección `https://...onrender.com`.
5. Abre esa dirección desde el celular. En Android/Chrome puedes usar **Añadir a pantalla de inicio** para usarla como app.

## Importante

El juego actual funciona principalmente como panel de anfitriona. Esta publicación lo hace accesible por internet, pero todavía no conecta automáticamente los comentarios de TikTok/Facebook ni incorpora pagos.

Para una operación con varios teléfonos simultáneos y participantes conectados a sus propias tablas se necesitaría una capa de sesiones/base de datos en tiempo real.
