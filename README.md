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

---

# Informe de Visita GREPCON (app para toda la empresa)

Formulario de visita a técnicos en campo (7 pasos → resumen → PDF). Está en `informe/`.
Es una PWA con su propio icono: se instala gratis en Android e iPhone desde el navegador,
sin tiendas de apps.

- **Enlace para compartir:** https://richard1981canary.github.io/Grepcon-app/informe/
  (requiere GitHub Pages activado, ver paso 1 arriba).
- **Android (Chrome):** abrir el enlace → menú ⋮ → *Instalar app*.
- **iPhone (Safari):** abrir el enlace → Compartir → *Añadir a pantalla de inicio*.
- En el visor del PDF, **📤 Compartir** abre la hoja del móvil (WhatsApp, correo, Teams…).
- Funciona sin conexión una vez abierta por primera vez.

Al publicar cambios, sube `VERSION` en `informe/sw.js` para que las apps instaladas se actualicen.
