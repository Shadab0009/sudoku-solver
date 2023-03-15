Sudoku Solver using Digital Image Processing with Python, TensorFlow, and Computer Vision
This project implements a Sudoku solver that uses digital image processing techniques and machine learning algorithms to recognize the digits in a Sudoku puzzle image and solve the puzzle. The solver is built using Python, OpenCV, TensorFlow, and NumPy.

Installation
Install the required packages: pip install -r requirements.txt
Download the trained TensorFlow model: model.h5
Save the model.h5 file to the models directory.


Usage
Open the Jupyter notebook Sudoku_Solver.ipynb.
Run the notebook cell by cell to understand the steps involved in the Sudoku solving process.
To test the solver on a new Sudoku puzzle image, replace the input.jpg file in the images directory with your own image.
Run the last cell in the notebook to solve the puzzle.
The solved Sudoku puzzle will be displayed on the output image and saved to the images directory.


Project Structure
Sudoku_Solver.ipynb: Jupyter notebook containing the project code and explanations.
models/model.h5: Trained TensorFlow model for digit recognition.
images/input.jpg: Sample input Sudoku puzzle image.
images/output.jpg: Output image with the solved puzzle.
utils.py: Utility functions for image preprocessing and cell extraction.
solver.py: Sudoku solver algorithm based on backtracking.


References
OpenCV Documentation
TensorFlow Documentation
NumPy Documentation
Sudoku Solver Algorithm
