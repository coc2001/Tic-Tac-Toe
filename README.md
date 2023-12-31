# Tic-Tac-Toe
This is a simple implementation of the Tic Tac Toe game in C++. The game allows two players to take turns and play against each other on a 3x3 grid.

**Features**<br>
* Player vs Player: Two human players can play against each other.<br>
* Valid Move Checking: The game validates each move to ensure it is within the bounds of the board and the selected cell is not already occupied.<br>
* Winning Condition: The game checks for winning conditions after each move to determine if a player has won or if it's a draw.<br>
* Turn-based Gameplay: The game alternates turns between the two players until there is a winner or a draw.<br>
* Display Board: The current state of the board is displayed after each move, allowing players to see the progress of the game.<br>
* Input Validation: User input is validated to ensure it is in the correct format and within the valid range of choices.<br>
* Restart Option: After a game ends, players have the option to restart and play again.<br>

**How to Play**<br>
* The game starts by displaying an empty 3x3 grid.<br>
* Player 1 is assigned the symbol 'X', and Player 2 is assigned the symbol 'O'.<br>
* Players take turns entering their move by specifying the row and column numbers of the cell they want to mark. For example, entering "1 1" would mark the cell at the top-left corner.<br>
* The game validates the move and checks for a winning condition or a draw. If a winner is found, the game displays the result and asks if the players want to play again. If it's a draw, the game also displays the result and offers a restart option.<br>
* If the players choose to play again, the game resets the board and assigns the next player as Player 1.<br>
