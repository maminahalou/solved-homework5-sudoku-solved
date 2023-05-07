Download Link: https://assignmentchef.com/product/solved-homework5-sudoku-solved
<br>
SUDOKU Rules: A puzzle looks like the one on the previous page: a 9×9grid with some numbers filled in. The challenge is to fill in each emptyspace with a digit 1 through 9, so that no digit is repeated in any row,column or “block”. “Block” is my name for the nine 3×3 blocks outlinedin thicker black lines in the picture.

Your Assignment: In the Eclipse workspace of your choice, create anew Java project containing package “sudoku”. Import the 4 starter filesthat you downloaded with this assignment: Evaluation.java, Grid.java,Solver.java, and TestGridSupplier.java. You won’t need to changeEvaluation.java or TestGridSupplier.java. Your assignment is to finishGrid.java and Solver.java.

Grid: This class models a Sudoku puzzle that is unsolved, partiallysolved, or completely solved. The class has a 9×9 array of ints, called“values”. If a Sudoku square is empty, the corresponding cell in “values”is zero; otherwise the cell in “values” contains the number in the Sudokusquare. The starter class has a ctor and a toString() method that youshould not change. It also has 4 empty methods that you need to write:next9Grids(), isLegal(), isFull(), and equals(). Do not change theirnames, arg lists, or return types. The comments on the unfinishedmethods tell you all you need to know about what they should do. It’s okto add more methods to this class.

You don’t need to provide this class with hashCode() or compareTo()methods. The equals() method is just so that you can compare yourpuzzle solutions to solutions in TestGridSupplier. (That is, you won’t becollecting Grid instances into a hash set a tree set.)

Solver: Most of this class has already been written. Complete thesolveRecurse() method using the backtracking technique you saw inlecture and lab. Also complete the evaluate() method. The main()method is for you to use while testing your code with the puzzles andsolutions in TestGridSupplier.

Evaluation: You saw this enum in lecture and lab. It contains 3 valuesthat represent the 3 possible outcomes of the evaluate() method of theGrid class. Look at the source code. Sometimes enums can becomplicated, but this one is not. You might need to write a simple enumfor the next midterm.

TestGridSupplier: This class contains static methods that return Gridinstances. Some of them are puzzles, some are solutions, and some arefor testing your code