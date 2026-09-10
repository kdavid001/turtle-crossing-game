# Turtle Crossing Game

A simple, beginner-friendly arcade game built with Python's turtle module. Guide the turtle across the road while avoiding cars — a small project to practice game loops, collision detection, and object-oriented design.

![Game screenshot](Screenshot.png)

## Features
- Move a player turtle from bottom to top of the screen to score points.
- Randomly spawning cars that travel across the screen at increasing speed.
- Scoreboard that tracks player progress.

## Requirements
- Python 3.8+ (the turtle module is included in the standard library)

## Files
- `main.py` — game entry point (run this to start the game)
- `player.py` — player (turtle) class and movement controls
- `car_manager.py` — spawns and moves cars across the screen
- `scoreboard.py` — displays and updates the score
- `Screenshot.png` — gameplay screenshot used in this README

## Controls
- Up arrow — move the turtle forward

## How to run
1. Make sure you have Python 3 installed: `python --version`
2. From the repository root, run:

```bash
python main.py
```

The game opens in a new window using the turtle graphics library.

## Notes
- This is a small learning project; feel free to fork and experiment with features such as multiple lanes, lives, or power-ups.

---
Updated README to include description, run instructions, and a screenshot.
