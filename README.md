# 🐍 3D Snake Game

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Three.js](https://img.shields.io/badge/Three.js-000000?logo=three.js&logoColor=white)](https://threejs.org/)

A modern browser-based 3D Snake game built with HTML, CSS, and JavaScript, powered by Three.js for immersive visuals, lighting, shadows, and animated game objects.

## Overview
This project transforms the classic Snake experience into a visually rich 3D environment with:
- a glowing game board and grid
- animated snake segments and food
- dynamic lighting and shadow effects
- keyboard controls with arrow keys or WASD
- score tracking and restart gameplay
- wrap-around movement at the edges of the board

## Technologies Used
- HTML5 for the game structure and UI
- CSS3 for styling, layout, overlays, and responsive interface elements
- JavaScript (ES Modules) for game logic and interaction
- Three.js for 3D rendering, meshes, materials, lighting, and animation
- OrbitControls for camera movement and perspective control
- WebGL rendering via the browser
- Import maps for module-based asset loading from CDN

## Features
- 3D snake movement with a distinct head and body segments
- Animated food with floating and rotating effects
- Realistic lighting, shadow casting, and a dark neon-inspired visual theme
- Score display and replay button
- Self-collision detection and continuous board wrap-around gameplay
- Smooth camera controls using mouse drag/zoom behavior

## How to Play
1. Open [index.html](index.html) in a modern web browser.
2. Use the arrow keys or WASD to move the snake.
3. Eat the glowing red food to grow and increase your score.
4. Avoid colliding with your own body.
5. The snake will continue moving by wrapping around the board edges.

## Running Locally
If you want to run it from a local server for a smoother experience, use:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Project Structure
- [index.html](index.html) - Main game file containing HTML, CSS, Three.js setup, scene creation, gameplay logic, and animation loop

## Future Development
This project is designed to be easy to extend and improve. Possible future upgrades include:
- sound effects and background music
- levels and difficulty modes
- power-ups and obstacles
- score persistence and leaderboards
- mobile touch controls

## License
This project is licensed under the MIT License.

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
