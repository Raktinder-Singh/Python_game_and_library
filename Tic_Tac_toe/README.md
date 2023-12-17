This Python code implements a simple two-player Tic Tac Toe game. Here's a brief description of the code:

The intro() function provides an introduction to the Tic Tac Toe game, explaining the rules and prompting the user to press Enter to continue.

The create_grid() function initializes a 3x3 empty game board.

The sym() function allows players to choose their symbols (X or O) and informs them of their assigned symbols.

The startGamming() function takes care of player turns, validates user inputs, and updates the game board accordingly.

The isFull() function checks if the board is full or if there's a winner after each move. It calls the startGamming() function in a loop until the game is over.

The outOfBoard() function informs players if their selection is out of the board's range.

The printPretty() function prints the Tic Tac Toe board in a visually appealing format.

The isWinner() function checks if any player has won the game by examining rows, columns, and diagonals.

The illegal() function informs players if they attempt to choose a square that is already filled.

The report() function displays the game summary, indicating the winner or a tie.

Finally, the main() function serves as the entry point, calling the other functions to execute the Tic Tac Toe game.



**Some screenshots of the output is in the output folder.**
