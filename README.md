Solves Sudoku puzzles.
First try to solve by filling in the cells with only one possibility.
If it cannot go any further, use a backtracking DFS (depth-first search)
algorithm to try the possible solutions. As soon as a solution is found,
it terminates the algorithm and prints it out.
The algorithm assumes that empty cells are denoted with a 0.



# Sudoku-Solver
First the program scans each cell and if there exists only one possibility, then it inserts that number.  The program does this until the puzzle is stuck. Then it runs a backtracking DFS search to "try out" the possibilities, eliminating those (and its children) that doesn't work.
