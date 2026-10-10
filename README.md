# Tetris GREPCON HSE

Juego de Tetris con la marca GREPCON HSE. Cada pieza lleva una letra de **G·R·E·P·C·O·N**
con colores de señalización de seguridad. Al limpiar líneas aparecen consejos HSE y suma
"días sin accidentes"; limpiar 4 líneas a la vez da un **¡HSE PERFECTO!**.

## Jugar

Abre `index.html` en el navegador (no necesita instalación).

- `←` `→` mover · `↑` / `X` girar · `Z` girar al revés
- `↓` bajar · `Espacio` caída rápida · `P` pausa
- En móvil aparecen botones táctiles.

## Logo

El logo está recreado en SVG dentro de `index.html`; la imagen original está en `logo-original.jpg`.

## Instalar como app (Android / iPhone)

El juego es una PWA: se instala desde el navegador y funciona sin internet.

1. Publicar (una vez): en GitHub, *Settings → Pages → Source: Deploy from a branch*,
   rama `claude/tetris-grepcon-hse-game-fcfeus`, carpeta `/ (root)` → *Save*.
2. Enlace para compartir: https://richard1981canary.github.io/Grepcon-app/
3. Instalar:
   - **Android (Chrome):** menú ⋮ → *Instalar app* / *Añadir a pantalla de inicio*.
   - **iPhone (Safari):** botón Compartir → *Añadir a pantalla de inicio*.

Al publicar cambios, sube `VERSION` en `sw.js` para que las apps instaladas se actualicen.
