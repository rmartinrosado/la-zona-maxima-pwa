# La Zona Máxima PWA (actualizada)

## Publicar en GitHub Pages
1. Descarga y descomprime `la-zona-maxima-pwa-actualizada.zip`.
2. Sube **el contenido** de esta carpeta al repositorio `la-zona-maxima-pwa` (reemplaza `index.html`, `manifest.webmanifest`, `sw.js` y `assets/`).
3. En GitHub → Settings → Pages, deja `main` y `/(root)`.
4. Abre la URL de GitHub Pages en Safari y recarga. Si se muestra la versión anterior, elimina la PWA de la pantalla de inicio, abre la web en Safari, recarga y vuelve a añadirla.

## Funciones
- Menú desplegable por país/categoría y segundo menú por grupo.
- Búsqueda de canales.
- Reproductor nativo de Safari.
- Carga de otros TXT/M3U; filtra enlaces a HTTPS HLS (`.m3u8`) y excluye HTTP, MPD/DASH y directivas DRM `KODIPROP`.
- Si un canal falla, permite quitarlo de la lista activa y exportar el TXT actualizado.

## Importante
La lista incluida contiene únicamente enlaces HTTPS HLS sin DRM de Kodi que parecen compatibles con Safari. **No se ha podido verificar desde el entorno de creación si cada servidor responde o si el stream sigue activo**; eso requiere probarlo en tu iPhone y red. Un enlace `.m3u8` puede seguir fallando por caducidad, bloqueo geográfico, autorización, CORS/servidor o baja del canal. Los canales eliminados desde la interfaz solo se quitan de la sesión; pulsa Exportar para guardar el TXT depurado.
