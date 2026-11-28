# Bruno's Big Adventure

A side-scrolling platformer starring Bruno the golden retriever. Collect bones, bop the critters and reach the doghouse across three levels.

## Play

Open `index.html` in any modern browser. There is nothing to install or build.

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move | Arrow keys or A / D | ◀ ▶ buttons |
| Jump | Space, W or Up | JUMP |
| Bark (stuns nearby critters) | X, K or B | WOOF |
| Pause | P | |
| Mute | M | |

## How it's built

One self-contained HTML file with no dependencies:

- HTML5 Canvas 2D for all graphics, drawn in code (no image files)
- Vanilla JavaScript for the game loop, physics and tile collisions
- Web Audio API for synthesised sound effects and background music (no audio files)
- `localStorage` for the best score

## Hosting

Serve `index.html` from any static host, for example GitHub Pages. To embed it in an existing page:

```html
<iframe src="index.html" style="width:100%;aspect-ratio:16/9;border:0" allowfullscreen></iframe>
```
