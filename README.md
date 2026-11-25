```markdown
# PacMan Game using OpenGL

A 2D PacMan game built with C++ and OpenGL/GLUT, developed as a mini project 

## Overview

This project recreates the classic PacMan arcade experience using OpenGL functions for rendering, animation, and user interaction. The game features a menu-driven start screen, keyboard-controlled PacMan movement, scoring, and ghost entities (red circles).

## Features

- **Menu System** – Start/Exit options via right-click menu
- **Keyboard Controls** – Arrow keys to move PacMan
- **Scoring System** – Collect pellets to increase score
- **Ghost Entities** – Red obstacles scattered across the play field
- **2D Rendering** – Built with OpenGL primitives (points, circles, text)

## Requirements

### Software
- **OS:** Ubuntu WSL on Windows 11 (or native Linux)
- **IDE:** Visual Studio Code
- **Libraries:** OpenGL, GLUT (freeglut)

### Hardware
- **CPU:** Intel Core i5-11300H (or equivalent)
- **RAM:** 8GB
- **Storage:** SSD recommended
- **Display:** Standard laptop display
- **Input:** Keyboard and mouse

## Installation & Build

```bash
# Install dependencies (Ubuntu/Debian)
sudo apt-get update
sudo apt-get install freeglut3-dev build-essential

# Compile
g++ pacman.cpp -o pacman -lGL -lGLU -lglut

# Run
./pacman
```

## Controls

| Input | Action |
|-------|--------|
| ↑ ↓ ← → | Move PacMan |
| Right-click | Open menu (Start / Exit) |

## Snapshots

| Introduction Window | Game Window |
|---|---|
| Start screen with team credits | PacMan gameplay with score and ghosts |

## Project Structure

```
├── pacman.cpp          # Main source code
├── README.md           # This file
└── report.pdf          # Full project report (optional)
```

## License

This project is submitted for academic purposes. Feel free to reference or build upon it with attribution.

