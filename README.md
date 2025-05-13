# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from the matrix and assign in np.array()
### Step 3: Use the np.linalg.inv() fun
### Step 4: End the program.



## Program:
```
#Program to find the inverse of a matrix.
#Developed by: kannan R
#RegisterNumber:212224240072
import numpy as np
matrix = np.array([[2,1,1],
                   [1,1,1],
                   [1,-1,2]])
inverse_matrix = np.linalg.inv(matrix)
print(inverse_matrix)
```
## Output:
![alt text](image.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

