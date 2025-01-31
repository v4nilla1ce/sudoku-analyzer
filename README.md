# Sudoku Solver & Visualizer

## Description
This project provides a Sudoku solver and visualizer using Python. It includes functions to process Sudoku puzzles, compute values, and visualize the results using Matplotlib.

## Features
- Parses a Sudoku puzzle into a structured format
- Computes possible values for each empty cell
- Visualizes the Sudoku puzzle's zero-value distribution in 3D

## File Overview

### `expDict.py`
Contains functions to process the Sudoku puzzle into a structured dictionary, facilitating further computations.

### `importPuzzle.py`
Handles Sudoku puzzle imports (currently a placeholder with `Tkinter`).

### `mainFile.py`
The main execution file that integrates puzzle processing and visualization.

### `plotFunc.py`
Handles visualization of Sudoku zero values in 3D using Matplotlib.

## Installation & Requirements
Ensure you have Python installed along with the required dependencies:

```bash
pip install numpy matplotlib
```

## Usage
Run the main script to process and visualize a Sudoku puzzle:

```bash
python mainFile.py
```

## License
This project is licensed under the MIT License.

