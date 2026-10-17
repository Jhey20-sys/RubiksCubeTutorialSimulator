# Rubik's Cube Tutorial Simulator

**Layer by Layer** is an interactive web app that teaches you to solve a 3×3 Rubik's Cube with the beginner's layer-by-layer method, using an animated 3D cube.

## Features

- **3D cube** you can drag to view from any angle, with animated face turns
- **Notation guide** for U, D, R, L, F, B, primes (`'`), half turns (`2`) and `y`, with a move pad to try each one
- **Seven lessons**, each with real example cases:
  1. White cross
  2. White corners
  3. Middle layer edges
  4. Yellow cross
  5. Match the yellow edges
  6. Put corners in their spots
  7. Twist the last corners
- **Algorithm playback**: play, pause, step forward and back, three speeds, and click any move to jump to it
- **Practice mode**: scramble, solve with on-screen keys or the keyboard, undo, timer, move counter and solve detection
- Progress tracking ("Mark as learned"), light and dark themes, and a phone-friendly layout

## Run it

Open `index.html` in a modern browser. No build step or install needed. An internet connection is required to load Three.js and the fonts from their CDNs.

## Keyboard

| Key | Action |
| --- | --- |
| `U` `D` `R` `L` `F` `B` | Turn that face clockwise (practice and notation) |
| `Shift` + key | Turn counter-clockwise |
| `Y` | Rotate the whole cube |
| `→` / `←` | Next / previous move (lessons) |
| `Space` | Play / pause (lessons) |

## Built with

- HTML, CSS and JavaScript
- [Three.js](https://threejs.org/) r128 for 3D rendering
