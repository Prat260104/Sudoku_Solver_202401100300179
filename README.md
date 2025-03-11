# Sudoku_Solver_202401100300179
Sudoku Solver Using Backtracking Algorithm
Description
This repository contains a Python implementation of a Sudoku solver using the Backtracking algorithm. The solver fills a partially completed 9x9 Sudoku grid and ensures that the solution adheres to the standard rules of Sudoku. The algorithm uses recursion and backtracking to try different possible numbers for empty cells until it finds a valid solution.

Features
The program accepts a Sudoku puzzle as input from the user.
It uses the Backtracking algorithm to solve the puzzle.
The solver checks whether placing a number in a specific cell is valid by ensuring it follows the rules of Sudoku (no repetition in the row, column, or 3x3 subgrid).
The solution is printed to the console, showing the completed Sudoku board.

Requirements
Python 3.x

Usage
To run the Sudoku solver:


Enter the Sudoku puzzle row by row (use 0 for empty cells):
Row 1: 5 3 0 0 7 0 0 0 0
Row 2: 6 0 0 1 9 5 0 0 0
Row 3: 0 9 8 0 0 0 0 6 0
Row 4: 8 0 0 0 6 0 0 0 3
Row 5: 4 0 0 8 0 3 0 0 1
Row 6: 7 0 0 0 2 0 0 0 6
Row 7: 0 6 0 0 0 0 2 8 0
Row 8: 0 0 0 4 1 9 0 0 5
Row 9: 0 0 0 0 8 0 0 7 9

Initial Sudoku Board:
5 3 . . 7 . . . .
6 . . 1 9 5 . . .
. 9 8 . . . . 6 .
8 . . . 6 . . . 3
4 . . 8 . 3 . . 1
7 . . . 2 . . . 6
. 6 . . . . 2 8 .
. . . 4 1 9 . . 5
. . . . 8 . . 7 9

Solved Sudoku Board:
5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9
Functions
print_board(board): Prints the Sudoku board.
is_valid(board, row, col, num): Checks if placing the number num at position (row, col) is valid according to Sudoku rules.
solve_sudoku(board): Solves the Sudoku puzzle using backtracking.
input_board(): Takes user input to generate the Sudoku board.
main(): The entry point of the program that runs the solver and displays the result.
Example Input and Output.
