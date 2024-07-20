# tic-tac-toe_java

Created game that uses following methods:
1. drawGame()
2. isValidSelection()
3. isPositionOpen()
4. checkForRowWin()
5. checkForColWin()
6. checkForDiagonalWin()

Step by step
1. Declare and initialize the two-dimensional array for the board.
2. Declare and initialize the one-dimensional char array with the symbols for the players.
3. Declare and initialize integers for col and row (with initial value 0).
4. Declare a validSelection boolean with an initial value of false (so the user is prompted for #input until the entry is valid).
5. Declare a Scanner for reading the user input.
6. Draw the initial empty board.
7. Set up a for loop to run up to nine times to handle the turns. (Even turns are X's turns and odd turns are O's turns).
8. Inside the for loop that handles the turns, set up a while loop that runs until the user makes a valid move.
9. In the while loop, prompt for the chosen row and column and read the input.
10. Check if the selected position is valid.
11. If the selected position is valid, check if the selected space is open.
12. If the position is valid and open, set the character for the select square and set variable so that the while loop ends.
13. Redraw the board.
14. Check for a win if the turn is the 5th iteration of the for loop.
15. At the bottom of the for loop, set the variable for the while loop so that the loop will run during the next iteration of the for loop.
