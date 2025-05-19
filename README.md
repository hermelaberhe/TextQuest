# TextQuest

**TextQuest** is a lightweight, text-based console game written in Java. The player controls a hero who moves across a linear board, encountering enemies and collecting treasure. This mini-game demonstrates object-oriented programming (OOP) fundamentals including inheritance, encapsulation, and collision detection logic.

## Features

- Move-forward mechanic (press Enter)
- Hero, enemy, and treasure entities
- Collision-based interactions
- ASCII-based board rendering

## Project Structure

- `Hero` – the player character with health and position
- `Entity` – base class for all board characters
- `Board` – handles rendering entities on a line
- `Game` – manages game loop and logic
- `Main` – entry point

## Getting Started

To run the game:

```bash
javac Main.java
java Main
