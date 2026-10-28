# UMARTPLACE — simulación de plataforma

Abre `index.html` en el navegador para recorrer la simulación.

- Los catálogos, perfiles, productos, reseñas y métricas son ejemplos visuales.
- El carrito, seguimiento y visitas se guardan localmente en el navegador.
- No se realizan pagos ni se generan ventas reales.
- La nota de compra se puede descargar como `.txt` o imprimir y guardar como PDF.
- Las notificaciones automáticas reales requieren una plataforma conectada a un servidor.

## Publicación automática en GitHub Pages

El flujo `.github/workflows/deploy-pages.yml` publica el sitio cuando se suben cambios a la rama `main`. Para activarlo, en el repositorio de GitHub entra a **Settings → Pages** y selecciona **GitHub Actions** como origen de publicación. Después de subir este archivo, cada `push` a `main` actualizará el sitio; la dirección aparecerá en esa misma sección y en la ejecución del flujo, dentro de **Actions**.
