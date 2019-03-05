# Sudoku Solver

A Python program to solve a given Sudoku. Along with Sudoku solver it can generate a random Sudoku.

## Functionality
1. Have Both console and graphics interface, console is better than graphics
2. Clear Whole Sudoku
3. Randomly Initilize Sudoku
4. Can check if it contain on provided elements
5. Can also check Correctness(constraint satisfied) and Completeness(no element to fill) of Sudoku.
6. Automatically solve the Sudoku
7. ...

## About files

### sudoku.py
It contain a Sudoku Class which deals with all the problems related with Sudoku

### application.py
It contain an Application Class which deals with all GUI concepts used in our project

### main.py
It a main file which create an object of Application and start its init function

### problems.txt
It contain some sample regarding to Sudoku

## Requirements
1. Python3
2. tkinter package
3. ...

## How to run

### For GUI version
```bash
python3 main.py
```

### For console version
```bash
python3
```
```python
from sudoku import Sudoku
a = Sudoku()
a.initPuzzle(True)
a.show()
a.autoSolve()
```

## Previews
### Empty Sudoku
![Empty Sudoku](https://github.com/B16CS006/Sudoku-Solver/blob/master/images/emptySudoku.png)
### Unfilled Sudoku
![Unfilled Sudoku](https://github.com/B16CS006/Sudoku-Solver/blob/master/images/unfilledSudoku.png)
### Filled Sudoku
![Filled Sudoku](https://github.com/B16CS006/Sudoku-Solver/blob/master/images/filledSudoku.png)
