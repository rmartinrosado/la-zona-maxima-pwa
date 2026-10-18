LA ZONA MAXIMA — PWA CON SECCION DE FUTBOL

CONTENIDO
- index.html: PWA con filtros por país/idioma, búsqueda, reproductor, acceso oficial a Yoigo TV y sección Fútbol y LaLiga.
- manifest.webmanifest y sw.js: instalación y caché de la PWA.
- La_Zona_Maxima_IPTV_por_pais_y_canal.m3u: lista global incluida.

NUEVA SECCION
- Acceso directo a https://yoigotv.yoigo.com/ y a la ayuda oficial de Yoigo TV. El inicio de sesión se realiza en Yoigo; la PWA no almacena credenciales ni integra el reproductor protegido.
- Acceso a la programación oficial de M+ LALIGA y M+ LALIGA 2.
- Calendario oficial de LaLiga.
- Enlace a lista M3U pública de canales deportivos. Para cargarla: abre el enlace, guarda el archivo si el navegador lo permite y usa el selector «Cargar lista M3U/M3U8» de la app.
- Botón para filtrar canales de fútbol dentro de la lista cargada. Es un filtro aproximado por nombre/metadatos.

PUBLICAR EN GITHUB PAGES
1. Descomprime el ZIP.
2. En el repositorio de GitHub, sube y reemplaza index.html, manifest.webmanifest, sw.js y La_Zona_Maxima_IPTV_por_pais_y_canal.m3u en la raíz.
3. Espera a que GitHub Pages publique los cambios.
4. En el iPhone, cierra la PWA por completo y vuelve a abrirla. Si sigue la versión anterior, abre la web en Safari y recarga; el service worker ahora usa una caché nueva.

IMPORTANTE
Los enlaces de Movistar son oficiales y pueden exigir una suscripción. La lista pública de deportes no es una lista de Movistar LaLiga ni garantiza que todos los canales estén disponibles en España o se reproduzcan en Safari. La PWA no incluye credenciales ni evita suscripciones, DRM o restricciones geográficas.
