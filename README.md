# Sudoku

The code is written in Python 3, mainly from <https://github.com/XujinLeo/every-week-practice/raw/master/solveSudoku/solveSudoku.py> </br>
Just input your sudoku puzzle, use 0 to present any vacant position, from left to right, top to bottom, totally 81 digits. </br>
Example:
```
$ python3 sudoku.py 004002300030000502250000897000720000000030000000094000849000016103000080006100900
Your input:
+-----+-----+-----+
|    4|    2|3    |
|  3  |     |5   2|
|2 5  |     |8 9 7|
+-----+-----+-----+
|     |7 2  |     |
|     |  3  |     |
|     |  9 4|     |
+-----+-----+-----+
|8 4 9|     |  1 6|
|1   3|     |  8  |
|    6|1    |9    |
+-----+-----+-----+
Result:
+-----+-----+-----+
|9 8 4|5 7 2|3 6 1|
|6 3 7|9 1 8|5 4 2|
|2 5 1|3 4 6|8 9 7|
+-----+-----+-----+
|3 6 8|7 2 1|4 5 9|
|4 9 2|6 3 5|1 7 8|
|7 1 5|8 9 4|6 2 3|
+-----+-----+-----+
|8 4 9|2 5 3|7 1 6|
|1 7 3|4 6 9|2 8 5|
|5 2 6|1 8 7|9 3 4|
+-----+-----+-----+
```
