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
### Step 4: End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: KARTHICK BALAJI S
#RegisterNumber: 212225040174
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
x=np.linalg.matrix_rank(A)
print(x)
```
## Output:
<img width="465" height="173" alt="image" src="https://github.com/user-attachments/assets/1bf9006a-9831-4513-874d-bc0a6a4027cb" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

