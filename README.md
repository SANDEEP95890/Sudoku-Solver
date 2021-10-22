# Sudoku-Solver
First the program scans each cell and if there exists only one possibility, then it inserts that number.  The program does this until the puzzle is stuck. Then it runs a backtracking DFS search to "try out" the possibilities, eliminating those (and its children) that doesn't work.
