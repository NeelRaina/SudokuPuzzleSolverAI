# Sudoku-Solver

sudokus_start.txt contains 400 examples of unsolved sudokus initial layout as a string of 81 with 0 representing the blank spaces.

sudokus_finish.txt is the solved solutions of the 400 examples for validating the output.

driver.py is the program to solve a given input

output.txt is the output file containing the solved solution to driver.py

all_loop.py is the script which loops through all 400 examples, solves them, and checks the solutions with the final given solutions.

The solution is obtained using backtracking and Arc Consistency method.
