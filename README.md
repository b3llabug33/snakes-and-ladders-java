# Snakes and Ladders (Java)

A console-based Snakes and Ladders game written in Java. Supports two-player local play or a single player versus a computer opponent.

## Features

- Player vs Player and Player vs Bot modes
- 10×10 board with 5 snakes and 5 ladders
- Visual board printed to console after every turn, with labeled snake/ladder positions
- Dice rolls, position tracking, and win detection

## How to Run

```bash
javac src/core/*.java src/ui/*.java
java -cp src ui.GameConsoleUI
```

## Project Structure

```
src/
├── core/
│   ├── GameLogic.java       # Board state, movement, snake/ladder detection, win condition
│   └── ComputerPlayer.java  # Computer player (auto-rolls)
└── ui/
    └── GameConsoleUI.java   # Console interface and board rendering
```

## Requirements

- Java 11+
