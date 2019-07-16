# Sudoku-Game-Files

There are two files in this repo, for use in testing your Sudoku-solving app to see how efficiently it does the job.  The first, "sudokuTests.js" is an array containing 1000 arrays, each of which is a series of numbers or dashes, the dashes representing blank spaces in a sudoku puzzle and the numbers representing spaces where they are filled in.  The elements are ordered as one reads English text, starting at the top-left, going across the top row to the end, then reading the second-uppermost row from left-to-right, and so forth to the bottom-right corner.

The second file, sudokuResults.js, contains an array with 1000 array elements, each of which is the solution of the corresponding entry in the sudokuTests.js file.  For example, the 500th array in sudokuResults.js is the solution of the puzzle in the 500th array in the sudokuTest.js file.
