# TicTacToe in C (Player vs Computer)

This is a command-line implementation of the classic TicTacToe game written in C, where you play against the computer.

## Features

- **Player vs Computer**: Play against a simple AI.
- **Interactive Console UI**: Easy-to-use interface with prompts for user input.
- **Randomized Computer Moves**: The computer makes random moves, ensuring a different experience each game.
- **Win Detection**: Automatically detects and announces the winner or if there's a tie.

 **Clone the Repository**:
   ```bash
   git clone https://github.com/AKL001/TicTacToe-in-C.git
   cd TicTacToe-in-C
   ```
**Cd Directorie**:
  ```bash
  cd TicTacToe
  ```
**Compile the Code**:
  ```bash
  gcc -o tictactoe tictactoe.c
  ```
**Run the Game**:
  ```bash
  ./tictactoe
```
## Example Gameplay 
```
   |   |   
---|---|---
   |   |   
---|---|---
   |   |   

Your move (X)
Enter row (1-3): 2
Enter column (1-3): 2

   |   |   
---|---|---
   | X |   
---|---|---
   |   |   

Computer's move (O)...

 O |   |   
---|---|---
   | X |   
---|---|---
   |   |   

Your move (X)
Enter row (1-3): 
```
## Code Structure

The main game logic is contained in `tictactoe.c`. Here's a brief overview of the key functions:

- `resetBoard()`: Sets up an empty game board at the start of each game.
- `printBoard()`: Displays the current state of the board in the console.
- `checkFreeSpaces()`: Counts and returns the number of empty spaces left on the board.
- `playerMove()`: Prompts for and handles the player's move input.
- `computerMove()`: Generates a random valid move for the computer.
- `checkWinner()`: Checks if there's a winner after each move and returns the winning symbol ('X', 'O', or ' ' for no winner).
- `printWinner()`: Announces the game result (win, lose, or tie) based on the final board state.

## Contributing

Contributions are welcome! Here are some ways you can contribute to this project:

1. Report bugs and issues.
2. Suggest new features or improvements.
3. Submit pull requests with bug fixes or new features.

## Acknowledgments

- Inspired by the classic game of Tic-Tac-Toe.

## Contact

If you have any questions, feel free to reach out :

AKL001 - akarimlabib@gmail.com

Project Link: https://github.com/AKL001/TicTacToe-in-C
