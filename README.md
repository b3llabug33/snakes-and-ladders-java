# Snakes and Ladders (Java)

A console version of Snakes and Ladders. Play against a friend on the same computer, or against a bot that just rolls for itself.

## What it does

- Player vs Player or Player vs Bot
- 10x10 board (squares 1-100), 5 snakes and 5 ladders
- Prints the board to the console after every turn, with the snakes/ladders and both players marked on it
- Rolls dice, moves you, and calls the winner once someone hits 100

## How to Run

```bash
javac src/core/*.java src/ui/*.java
java -cp src ui.GameConsoleUI
```

## Project Structure

```
src/
├── core/
│   ├── GameLogic.java       # board state, movement, snake/ladder detection, win condition
│   └── ComputerPlayer.java  # bot player, just rolls like anyone else
└── ui/
    └── GameConsoleUI.java   # console interface and board printing
```

## Requirements

- Java 11+
