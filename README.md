# TicTacToe

This is a simple Tic-Tac-Toe game implemented in C. The game is played on a 3x3 grid, where the player competes against the computer. The player uses the 'X' symbol, while the computer uses the 'O' symbol. The objective is to get three of your symbols in a row, column, or diagonal before your opponent does.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [How to Play](#how-to-play)
- [Code Structure](#code-structure)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)

## Installation

1. Clone the repository:
```
git clone https://github.com/sleinkaraman/TicTacToe.git
```
2. Navigate to the project directory:
```
cd TicTacToe
```
3. Compile the program:
```
gcc main.c -o TicTacToe
```
## Usage

After compiling the program, you can start the game by running:
```
./TicTacToe
```
The game will prompt you to enter your moves and will display the game board after each turn. The computer will automatically make its move after the player.

## How to Play

- The game is played on a 3x3 grid.
- Players take turns placing their symbol (X or O) in one of the empty spots on the board.
- The first player to align three symbols horizontally, vertically, or diagonally wins the game.
- If the board is full and no player has aligned three symbols, the game ends in a tie.

## Code Structure

- main.c: This is the main file containing the implementation of the game.

#### Key Functions

- resetBoard(): Resets the game board to its initial empty state.
- printBoard(): Displays the current state of the board.
- checkFreeSpaces(): Checks how many free spaces are left on the board.
- playerMove(): Handles the player's move input and updates the board.
- computerMove(): Generates a random move for the computer.
- checkWinner(): Checks if there is a winner or if the game is a tie.
- printWinner(): Prints the result of the game (win, lose, or tie).

## Future Improvements

- Difficulty Levels: Implement different levels of difficulty for the computer AI.
- Graphical Interface: Create a GUI version of the game using a library like SDL or a web-based interface.
- Two-Player Mode: Add an option for two players to compete against each other.

## Contributing

Contributions are welcome! If you have suggestions or want to improve the code, feel free to fork the repository and create a pull request.
























