# StarView HUD v4

Mapa estelar interactivo tipo HUD con pantalla de bienvenida, instrucciones integradas y Google Tag Manager instalado.

## Google Tag Manager

Este paquete ya trae instalado el contenedor:

`GTM-5KX5WPLM`

## Para ver cuánta gente la usa

GitHub Pages no guarda estadísticas privadas por sí solo. Para ver usuarios activos, conecta este contenedor con Google Analytics 4 desde Google Tag Manager.

### Pasos rápidos

1. Crea una propiedad en Google Analytics 4.
2. Crea un flujo web con esta URL:
   `https://proyectoaireyconfort-lab.github.io/starview-hud/`
3. Copia el Measurement ID, algo como:
   `G-XXXXXXXXXX`
4. En Google Tag Manager crea una etiqueta:
   - Tipo: Google Analytics / Google tag
   - Tag ID: tu `G-XXXXXXXXXX`
   - Activador: All Pages
5. Guarda.
6. Toca **Enviar** en Tag Manager.
7. Publica la versión.

Después podrás ver usuarios activos en Google Analytics, en el reporte de tiempo real.

## Privacidad

La app no muestra contador público. Solo el dueño de la cuenta de Google Analytics / Tag Manager puede ver el uso.
La ubicación de la app se usa en el navegador para calcular el mapa; no se guarda en una base de datos propia.

## Archivos

- `index.html`
- `manifest.webmanifest`
- `README.md`
