# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A=np.array([[1,2,3],[3,6,9]])

B=np.linalg.matrix_rank(A)

print(B)

## Output:<img width="501" height="638" alt="{C0A15B22-765D-4117-97E4-9707664DD90C}" src="https://github.com/user-attachments/assets/433d99c5-2e32-443d-9b18-f64d3655a260" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

