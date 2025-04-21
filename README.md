# Rock Paper Scissors Game

## Overview
A simple console-based Rock Paper Scissors game implemented in Java. The player competes against the computer in this classic hand game.

## Features
- Single-player gameplay against a computer opponent
- Random computer selection
- Input validation
- Simple console interface

## How to Play
1. Compile the Java file:
   ```
   javac RockPaperScissorsGame.java
   ```
2. Run the application:
   ```
   java RockPaperScissorsGame
   ```
3. When prompted, enter your choice:
   - 0 for Rock
   - 1 for Paper
   - 2 for Scissors
4. The computer will randomly select its choice
5. The winner will be determined based on the classic Rock Paper Scissors rules:
   - Rock crushes Scissors
   - Paper covers Rock
   - Scissors cut Paper
   - Same choices result in a tie

## Game Rules
- Rock (0) beats Scissors (2)
- Paper (1) beats Rock (0)
- Scissors (2) beats Paper (1)
- Identical choices result in a tie

## Implementation Details
The game logic is implemented in Java using:
- `Scanner` class for user input
- `Math.random()` for generating the computer's choice
- Conditional statements to determine the winner

## Future Enhancements
- Add option for multiple rounds
- Implement score tracking
- Create a graphical user interface
- Add different game modes (e.g., Rock Paper Scissors Lizard Spock)
- Implement different difficulty levels for the computer

## Requirements
- Java Development Kit (JDK) 8 or higher

