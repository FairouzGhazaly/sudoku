Functions:
1. solve(bo)

This function recursively solves the Sudoku puzzle using a backtracking approach.
It finds an empty cell, attempts to fill it with a number (1 to 9), and checks if the move is valid.
If a solution is found, the function returns True; otherwise, it backtracks and explores other possibilities.

2. valid(bo, num, pos)

This function checks the validity of placing a number (num) at a given position (pos) on the Sudoku board (bo).
It checks the row, column, and the 3x3 box to ensure the placement is valid.

3. print_board(bo)

This function prints the Sudoku board in a readable format, separating the 3x3 subgrids with lines.

4. find_empty(bo)
   
This function searches for an empty cell (denoted by 0) on the Sudoku board (bo).
If an empty cell is found, it returns the position as a tuple (row, col); otherwise, it returns None.

Usage:
1. Define the Sudoku puzzle in the board variable as a 9x9 matrix.
2. Call the print_board(board) function to display the initial puzzle.
3. Call the solve(board) function to solve the puzzle using the backtracking algorithm.
4. Call the print_board(board) function again to display the solved puzzle.
