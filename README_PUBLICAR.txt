DEMO REPORTE DIARIO — PUBLICACIÓN WEB

Contenido:
- index.html: aplicación demo
- manifest.webmanifest: configuración PWA
- service-worker.js: caché/offline básico para la demo
- icons/: carpeta reservada para iconos PWA

PUBLICACIÓN:
1. Subir TODOS estos archivos a un hosting estático que entregue HTTPS.
2. Abrir la URL pública desde Safari.
3. En iPhone: Safari > Compartir > Añadir a pantalla de inicio.

IMPORTANTE:
Esta demo no tiene todavía backend, usuarios reales ni sincronización multiusuario.
El modo offline de esta demo es local al navegador/dispositivo.
La versión real deberá añadir autenticación, base central, sincronización y control de conflictos.
