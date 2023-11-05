# Tic-Tac-Toe-game.


Tic-Tac-Toe game for a square game board of size n x n.<br>

The code you provided is an implementation of a simple console-based Tic-Tac-Toe game in Java. Here's a breakdown of how the code works:<br>

The program starts by asking the user to enter the size of the game board. The size is stored in the variable n, which represents an n x n game board.<br>

A 2D array board is created to represent the game board, where each cell in the array can have one of three values:<br>

0: An empty cell<br>
1: Cell occupied by Player 1<br>
2: Cell occupied by Player 2<br>
The variable player is used to keep track of the current player. It starts as Player 1, and the game continues in turns between Player 1 and Player 2.<br>

The variable winner is initially set to 0, and it is used to determine the winner. When a player wins, the value of winner is updated to the winning player (1 or 2), and the game loop ends.<br>

Inside the game loop, players take turns to make their moves. They enter row and column numbers to place their marks (X or O) on the board.<br>

The code checks if the chosen cell is empty. If it is, the player's mark is placed in that cell. If the cell is already occupied, an error message is displayed, and the player must try again.<br>

After each move, the printBoard function is called to display the current state of the game board.<br>

The code then checks for a win condition by counting the number of marks in the current row, column, main diagonal, and cross diagonal. If any of these counts reach n, the player with the matching marks is declared the winner, and the game ends.<br>

If no player has won, the turn switches to the other player for the next iteration of the game loop.<br>

The game continues until a player wins, at which point a message is displayed announcing the winner.<br>

The printBoard function is used to display the game board, showing the marks of each player.<br>

Overall, this code provides a basic implementation of a Tic-Tac-Toe game for a square game board of size n x n. Players take turns making moves, and the game continues until a player wins or the board is completely filled, resulting in a draw.<br>
