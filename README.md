# snake-game

A simple, single-file Snake game implemented in HTML/CSS/JavaScript.

## Features

- Fixed food RNG to use the full grid so food can appear in any cell.
- Ensures food never spawns on the snake.
- Prevents immediate reverse input when the snake's length is greater than 1.
- Pause / Resume and Restart buttons.
- Touch swipe controls for mobile.

## How to run

1. Open `index.html` in your browser (double-click or use a local server).
2. Controls: Arrow keys or WASD to move, Space to pause/resume, swipe on touch devices.

For local server testing:

```bash
# from the repo root
python -m http.server 8000
# then open http://localhost:8000/index.html
```

Enjoy! Pull requests and improvements welcome.
