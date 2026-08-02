# Shapes Game

A tiny interactive web page featuring three hoverable shapes — a square, a diamond, and a circle — built with plain HTML and CSS.

🔗 **Live demo:** [glistening-dodol-62188c.netlify.app](https://glistening-dodol-62188c.netlify.app/)

## Overview

This project renders three numbered shapes centered on the page:

| Shape   | Number | Hover Color |
|---------|--------|-------------|
| Square  | 1      | Red         |
| Diamond | 2      | Blue        |
| Circle  | 3      | Green       |

Hovering over any shape changes its background color, giving the page a simple, playful interactive feel.

## Project Structure

```
.
├── index.html   # Page markup and shape structure
└── style.css    # Layout, shapes, and hover effects
```

## How It Works

- **Layout:** `#main` uses Flexbox to center all shapes in the middle of the viewport.
- **Square:** A basic `200px x 200px` bordered box.
- **Diamond:** Created by rotating a square `45deg`; its inner text (`h1`) is rotated `-45deg` to counteract the tilt and stay upright.
- **Circle:** A square with `border-radius: 50%` to make it fully round.
- **Hover states:** Each shape has its own `:hover` rule that changes its `background-color`.

## Getting Started

No build tools or dependencies are required.

1. Clone or download this repository.
2. Open `index.html` directly in your browser.

That's it — the page will render immediately.

## Customization Ideas

- Add click interactions (e.g., alert, animation, or sound) using JavaScript.
- Add more shapes (triangle, star, hexagon) to expand the game.
- Turn it into an actual "game" by adding a scoring or matching mechanic.
- Adjust colors, sizes, and fonts in `style.css` to match your own theme.

## License

Feel free to use and modify this project for personal or educational purposes.
