# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy library
### Step 2: create a matrix using numpy
### Step 3: calc the result using np.linalg.inv
### Step 4: End the Program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: M.AADHAVAN NAGARAJAN
#RegisterNumber: 212225040001

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

Matrix=np.array([[2,1,1],[1,1,1],[1,-1,2]])

Result=np.linalg.inv(Matrix)
print(Result)
```
## Output:
<img width="1517" height="905" alt="image" src="https://github.com/user-attachments/assets/124eda44-8d6d-4f6a-b890-bdc60db43e00" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

