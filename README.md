# Pacman JS

Pacman JS is a browser-based JavaScript learning project: a small Pac-Man-style
board with keyboard movement, dots, scoring, a ghost, and an experimental AI.
It explores JavaScript fundamentals, animation timing, intervals, timeouts,
and the practical limits of precise browser timing.

## Run it

No build step or package installation is required. Open `index.html` in a
browser, or serve the directory locally:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000/` and use the keyboard to move.

## Project files

- `index.html` — board creation, game state, input, movement, scoring, and AI.
- `style.css` — board layout, sprites, and animation states.
- `sprite.png` — image atlas used by the player and ghost.

The AI remains experimental. Board coordinates in `window.blocks` affect its
behavior, and changing them can make the current pathing logic work better or
worse.
