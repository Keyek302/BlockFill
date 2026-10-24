# Block Fill

A mobile block puzzle on a square 8x8 board. Drag three pieces onto the grid and fill full rows or columns to clear them.

## Features
- Levels with score goals, a level select screen, and obstacle blocks that grow each level
- Daily challenge: one fixed puzzle per day, with a streak counter
- Endless mode
- Sound effects and vibration (toggle on the main menu)
- Installable PWA that works offline

## Play
Host on GitHub Pages: Settings -> Pages -> Deploy from branch -> `main` / root.
Then open `https://<your-username>.github.io/<repo-name>/` on your phone and tap **Install app** on the main menu
(or use Share -> Add to Home Screen on iPhone).

## Files
- `index.html`: the whole game (HTML, CSS and JS in one file)
- `manifest.webmanifest`: app name, colors, icons
- `sw.js`: service worker for offline play. If you change the game, bump `CACHE` (e.g. `block-fill-v2`) so players get the update
- `icon-192.png`, `icon-512.png`: app icons
