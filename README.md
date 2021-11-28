# sudoko-solver
a simple program to implement backtracking algorithm and solve the sudoko puzzle
algorithm-

    Start.
    Declare a matrix of N*N size where N=9.
    First, enter the values of the sudoku and enter 0 for the unassigned cells.
    Print the matrix first before solving.
    Declare a user-defined function of boolean type.
    Declare two variables rows and columns, and initialize them to -1.
    Check after assigning the current index of the puzzle is valid or not.
    If any number has a frequency greater than 1 return false else return true.
    Now, check for the unassigned location.
    If present then assigns a number from 1 to 9, check if assigning the number to the current index is valid or not.
    If valid then recursively call the function for all valid cases from 0 to 9.
    If any recursive call returns true, end the loop and return true.
    If no recursive call returns true then return false.
    If there is no unassigned location then return true.
    Display the result according to the boolean value received.
    If true, then print the solved sudoku puzzle.
    Else print that no solution exists.
    Stop.
