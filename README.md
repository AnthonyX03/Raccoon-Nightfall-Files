# Raccoon Nightfall Files

Juego HTML survival-horror (PWA) — fan-made, personajes originales.

## Dónde poner la música

Coloca estos **tres archivos MP3 en esta misma carpeta** (junto a `index.html`):

```
Raccoon_Nightfall/
├── index.html
├── manifest.json
├── sw.js
├── icon-192.png
├── icon-512.png
├── icon.svg
├── adrian.jpg
├── mara.jpg
├── Intro.mp3          ← menú / pantalla de inicio
├── AdrianCole.mp3     ← al jugar con Adrian (la intro se corta)
└── MaraVela.mp3       ← al jugar con Mara (la intro se corta)
```

Si falta un MP3, el juego sigue funcionando; solo no sonará esa pista.

## Instalar como PWA

1. Sube la carpeta a GitHub Pages, Netlify, o sirve en local con HTTPS/`localhost`.
2. Abre el juego en Chrome / Edge / Safari (móvil o escritorio).
3. Menú del navegador → **Instalar aplicación** / **Añadir a pantalla de inicio**.

En escritorio suele aparecer un icono ⊕ en la barra de direcciones.

## Controles

- Elige personaje y dificultad (**Nueva partida** no carga guardados viejos).
- **Continuar** recupera partidas.
- Zonas seguras: guardar y baúl.
- Mapa, inventario, equipo, ajustes (reiniciar partida).

## Créditos

Fan-made. Sin recursos oficiales de Capcom.
