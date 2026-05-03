# StarView HUD

Mapa básico del cielo visible desde tu ubicación.

## Cómo usar

1. Abre `index.html` en el navegador.
2. Presiona **Usar ubicación del celular** o escribe latitud y longitud.
3. Presiona **Actualizar cielo**.

## Listo para GitHub Pages

Este proyecto es completamente estático. No ocupa Python, servidor ni base de datos.

### Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo: `starview-hud`.
2. Sube estos archivos:
   - `index.html`
   - `manifest.webmanifest`
   - `.nojekyll`
   - `README.md`
3. En GitHub ve a:
   **Settings > Pages**
4. En **Build and deployment**, elige:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Guarda y espera a que GitHub te dé tu enlace.

## Nota

La ubicación GPS funciona mejor cuando la página se abre desde HTTPS, como GitHub Pages.
