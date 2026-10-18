LA ZONA MAXIMA — CORRECCION DE PERSISTENCIA

Corrección:
- La lista M3U que importes se guarda en IndexedDB del navegador/PWA del iPhone.
- Al cerrar y volver a abrir, se restaura primero la última lista importada.
- Se añade el botón “Borrar lista guardada” para eliminarla cuando quieras.
- Se ha cambiado la versión de caché del Service Worker para forzar la actualización.

Publicación:
1. Descomprime este ZIP.
2. Sube el contenido de La_Zona_Maxima_PWA_Futbol a la raíz del repositorio GitHub Pages y reemplaza los archivos.
3. Espera la publicación, cierra completamente la PWA y vuelve a abrirla.
4. Importa una lista una sola vez. La próxima vez debería seguir cargada.

La lista se guarda localmente en ese navegador/dispositivo. Si borras los datos del sitio o abres la PWA en otro dispositivo, tendrás que importarla allí también.
