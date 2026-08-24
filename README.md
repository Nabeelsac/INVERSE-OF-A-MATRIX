# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program
## Program:
```
#Program to find the inverse of a matrix.
#Developed by:Johan Renish A 
#RegisterNumber:212225040159
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[6,2,3],[3,1,1,],[10,3,4]])
b=np.linalg.inv(a)
print(b)
```
## Output:
<img width="1353" height="823" alt="Exp -3" src="https://github.com/user-attachments/assets/655ec31c-7741-4eb2-8638-7c8ab2fd22a0" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

