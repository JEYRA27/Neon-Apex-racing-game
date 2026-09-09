# NEON APEX

Standalone HTML5 arcade racing game. No build step or external game assets are required.

## Run

Open `index.html` in a modern browser, or from this folder run a local static server such as:

```powershell
python -m http.server 4173
```

Then visit `http://localhost:4173`.

## Controls

- **Desktop:** Arrow keys or A/D steer; Space uses nitro; Down/S brakes; Escape pauses.
- **Touch:** hold the on-screen steering or nitro buttons.

## Extending

Cars and environment palettes live at the top of `game.js` in `CONFIG`. Add a car object to `CONFIG.cars`, or a palette object to `CONFIG.tracks`; the garage and stat UI are data-driven. Game systems are grouped in `game.js` as Store, Audio, spawning, update/collision logic, drawing, and UI bindings.

