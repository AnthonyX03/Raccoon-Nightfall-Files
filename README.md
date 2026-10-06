# Raccoon Nightfall Files — v1.1

Juego HTML survival-horror instalable (PWA).

## Instalación PWA

**Importante:** no abras el juego como `file://`. Tiene que servirse por **HTTP(S)**:

- GitHub Pages / Netlify / Vercel, o
- En local: `npx serve .` / `python -m http.server` y entra en `http://localhost:8080`

### Android (Chrome)
Menú ⋮ → **Instalar aplicación** o **Añadir a pantalla de inicio**.

### iPhone (Safari)
Compartir → **Añadir a pantalla de inicio**.

### PC (Chrome / Edge)
Icono **Instalar** en la barra de direcciones.

## Música (opcional)

La reproducción ya no hace un `play → pause → play` al iniciar una partida. El sistema evita llamadas duplicadas a `play()` y conserva la pista actual hasta que realmente cambia de escena/personaje. El navegador puede bloquear el autoplay inicial; en ese caso la primera interacción del usuario desbloquea la música automáticamente.

En esta carpeta, junto a `index.html`:

- `Intro.mp3` — menú
- `AdrianCole.mp3` — partida Adrian
- `MaraVela.mp3` — partida Mara

## Archivos

- `index.html` — juego
- `manifest.json` / `sw.js` — PWA
- `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`
- `adrian.jpg`, `mara.jpg`
