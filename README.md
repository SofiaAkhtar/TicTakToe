# Extended Tic-Tac-Toe Game

Welcome to the Extended Tic-Tac-Toe Game! This Python script implements a classic Tic-Tac-Toe game with additional features such as player names, a replay option, and an improved user interface.

## Getting Started

### Requirements
- Python 3.x

### Installation
1. Clone the repository or download the script.
2. Ensure you have Python 3.x installed on your system.

### Usage
1. Run the script using a Python interpreter.
2. Enter the names of Player 1 (X) and Player 2 (O).
3. Follow the prompts to enter your moves in the format "row col."
4. Enjoy the game!

## Features
- Player names (customizable for each game).
- Replay option for continuous gameplay.
- Enhanced user interface with a clear board display.

## Gameplay Instructions
1. Players take turns entering their moves in the format "row col."
2. The game continues until a player wins or the board is full, resulting in a draw.
3. After each game, players have the option to play again or exit.

## Example

```bash
Welcome to Tic-Tac-Toe!

Enter name for Player 1 (X): Alice
Enter name for Player 2 (O): Bob

  0 | 1 | 2
  -----------
0 |   |   |  
  -----------
1 |   |   |  
  -----------
2 |   |   |  
  -----------

Alice, enter your move (row col): 1 1

  0 | 1 | 2
  -----------
0 |   |   |  
  -----------
1 |   | X |  
  -----------
2 |   |   |  
  -----------

Bob, enter your move (row col): 0 0

  0 | 1 | 2
  -----------
0 | O |   |  
  -----------
1 |   | X |  
  -----------
2 |   |   |  
  -----------

...

Bob wins!

Do you want to play again? (yes/no): no
Thanks for playing. Goodbye!
