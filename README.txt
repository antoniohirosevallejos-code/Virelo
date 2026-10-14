VIRELO V5 — VERSION DE PRUEBA

Qué incluye
- Marca provisional Virelo.
- Un video por operación.
- Tres salidas predeterminadas: vertical 1080x1920, cuadrada 1080x1080 y horizontal 1920x1080.
- Alternativa para crear solo una salida.
- Vista previa del video original y botón X para quitar la selección.
- Vista previa de cada resultado, descargas MP4 individuales y descarga ZIP.
- Opciones avanzadas para recortar los bordes SOLO del fondo difuminado.
- Botón de cancelación que intenta detener el motor y descarta resultados incompletos.
- Intenta mantener la pantalla encendida durante el procesamiento cuando el navegador lo permite.
- La salida ya no fuerza explícitamente 30 fps; se deja al motor conservar la cadencia temporal de entrada cuando sea viable.

Límites actuales
- Máximo 3 min 30 s por video (límite provisional).
- Salidas fijadas a 1080p/1080x1080; no exporta 4K.
- Requiere conexión a internet para descargar el motor FFmpeg.wasm y JSZip la primera vez o si no están en caché.
- El rendimiento depende del navegador, dispositivo, duración, códec, resolución y memoria disponible.
- El procesamiento de video no ha sido validado en una prueba de navegador real desde este empaquetado. Prueba V5 con videos cortos antes de reemplazar la versión anterior.

Acceso
La clave de acceso existente se mantiene: PandaFlow-20-Video
La clave se verifica localmente como en V4; esto es una barrera básica, no un sistema de licencias seguro.

Publicación
Sube el contenido de esta carpeta a la raíz del repositorio de GitHub Pages. Mantén juntos index.html, style.css, app.js y hero-skate.webp.

Aviso de licencia
La aplicación usa FFmpeg.wasm y descarga componentes desde CDN. Revisa y cumple las licencias de los componentes antes de distribuir comercialmente. FFmpeg.wasm/core está publicado bajo GPL-2.0-or-later.
