# Sudoku Solver using AI

Sudoku is a logic-based, combinatorial number-placement puzzle. In classic Sudoku, the objective is to fill a 9 × 9 grid with digits so that each column, each row, and each of the nine 3 × 3 subgrids that compose the grid contains all of the digits from 1 to 9.

Here, the riddle is solved using OpenCV, AI-CNN, and the backtracking algorithm. The sudoku image must first be cleaned and turned into a black and white image before contour identification can be done. CNN is fed with each contour in order to identify any digit that may be present. The backtracking algorithm is used to solve the puzzle once all of the digits have been identified. The user sees the finished solution superimposed on the original image.

## Dependencies
- OpenCV : 4.7.0
- Numpy : 1.25.0
- imutils : 0.5.4
- tensorflow : 2.15.0

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install any missing dependencies.

## Usage

- Download the repository and extract it into a folder
- Ensure python is installed in the machine. The code runs with python version 3.6 and above.
- Install any missing libraries mentioned above.
- Open a terminal/command-prompt and navigate to the folder where the files are extracted. 
- run the code using the following command
```bash
python main.py -i <path-to-sudoku-image>
```


## Results

After following are few examples of the output after executing the code.
![1.png](Results%2F1.png)

![2.png](Results%2F2.png)