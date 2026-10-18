# La Zona Máxima — PWA con filtros

## Incluye
- Filtro desplegable por país.
- Filtro estimado de canales en español/hispanos.
- Búsqueda por nombre.
- Orden por país y nombre del canal.
- Importación de archivos M3U/M3U8 desde Archivos en iPhone.
- Si `La_Zona_Maxima_IPTV_por_pais_y_canal.m3u` está en la raíz, intenta cargarla automáticamente.

## Publicar/actualizar en GitHub Pages
1. Descarga y descomprime el ZIP.
2. Sube `index.html`, `manifest.webmanifest`, `sw.js` y `La_Zona_Maxima_IPTV_por_pais_y_canal.m3u` al directorio raíz del repositorio de tu PWA.
3. Si GitHub pregunta si debe reemplazar `index.html` y `sw.js`, confirma para aplicar la nueva interfaz.
4. Espera a que GitHub Pages publique los cambios.
5. En iPhone, cierra la PWA y vuelve a abrirla. Si conserva la versión antigua, elimina la PWA de la pantalla de inicio y añádela otra vez desde Safari.

## Idioma: limitación
El filtro «Español / hispano» es una estimación basada en el país, el nombre del canal, el grupo y `tvg-id`. No detecta la pista de audio real de la emisión; algunos canales pueden quedar mal clasificados.

## Reproducción
Safari reproduce mejor emisiones HLS `.m3u8`. Los flujos DASH `.mpd`, DRM, autenticados o con restricciones geográficas pueden no funcionar. La app no elimina ni desbloquea protecciones.
