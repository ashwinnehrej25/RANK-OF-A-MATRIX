# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: end the program
## Program:
#Program to find the rank of a matrix.
#Developed by: K.Ashwin Nehrej
#RegisterNumber:212225220014
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[3, 2, 5],
              [1, 1, 2],
              [3, 3, 6]])

rank = np.linalg.matrix_rank(A)

print(rank
## Output:
<img width="1370" height="318" alt="image" src="https://github.com/user-attachments/assets/502ad3c8-5627-4065-8e2f-a03666de1748" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

