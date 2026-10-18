# LA ZONA MÁXIMA — PWA independiente

## Publicar en GitHub Pages
1. Crea un repositorio llamado `la-zona-maxima-pwa`.
2. Descomprime este ZIP y sube **el contenido** de la carpeta a la raíz del repositorio (no subas el ZIP).
3. Ve a **Settings → Pages**.
4. Selecciona **Deploy from a branch**, rama `main`, carpeta `/(root)` y pulsa **Save**.
5. Cuando se publique, abre la URL en Safari del iPhone → Compartir → Añadir a pantalla de inicio.

## Importar la lista
Abre la PWA, pulsa **Elegir archivo** y selecciona `LA ZONA MAXIMA.txt` desde Archivos. Se procesa localmente y no se envía al servidor. Al recargar, hay que importarla de nuevo.

## Compatibilidad y privacidad
La reproducción usa el elemento de vídeo HTML5. HLS puede funcionar en Safari si la fuente lo permite. Esta versión no incluye motor DASH ni aplica claves ClearKey; tampoco aplica automáticamente las cabeceras Kodi/VLC. No se han comprobado los enlaces. No subas la lista privada al repositorio. El service worker cachea solo la interfaz, nunca la lista ni los streams. Usa únicamente emisiones autorizadas.
