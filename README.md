# ASCII 3D Cube Visualizer

This C program displays a 3D animation of rotating cubes in the terminal using ASCII characters. It uses mathematical transformations and trigonometric functions to achieve a 3D rendering effect, with cross-platform support for `usleep` for smooth animations.

## Features
- ASCII-based 3D rendering of rotating cubes
- Customizable cube size and rotation speed
- Cross-platform compatible (Windows and Unix-based systems)

## Usage

### Compilation
To compile the code, use `gcc` with the math library:
```bash
gcc cube.c -o cube -lm

