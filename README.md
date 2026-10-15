# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Start the program and import NumPy 
### Step 2:Create a matrix using np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:Print the rank and stop the program
## Program:
import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A=np.array([[1,2,3],[3,6,9]])

B=np.linalg.matrix_rank(A)

print(B)

## Output:<img width="450" height="627" alt="Screenshot 2026-10-15 174605" src="https://github.com/user-attachments/assets/f7c6ad3a-a0d2-4337-8616-c52d1e09d0c0" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

