# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start the program and import NumPy
### Step 2: Create a matrix using np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Print the rank and stop the program.
## Program:
import os 

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A=np.array([[1,2,3],[3,6,9]])

B=np.linalg.matrix_rank(A)

print(B)

## Output:<img width="450" height="627" alt="{4457802C-36ED-4136-A561-5BC871C7ACA7}" src="https://github.com/user-attachments/assets/0f7b6d4c-a446-4269-bac2-fb87c86d6ae8" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

