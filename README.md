# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from the matrix and assign in np.array()
### Step 3: 
Use the np.linalg.inv() fun
### Step 4: 
End the program.


## Program:
```
#Program to find the inverse of a matrix.
#Developed by: DHANAPPRIYA S
#RegisterNumber:21222430056
import numpy as np
A = np.array([[1, 0, 3],
              [-1, 2, -2],
              [2, 3, -1]])

A_inv = np.linalg.inv(A)
print(A_inv)


```
## Output:

<img width="1207" height="896" alt="image" src="https://github.com/user-attachments/assets/172f47bb-6298-4e1b-982f-d2909e9cef59" />


## Result:
Thus the inverse of given matrix is successfully solved using python program
