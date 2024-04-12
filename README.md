# Date: 06/04/2024 
# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
Developed by: Subha Shree U
Register number: 2305002025

import numpy as py
a=np.array([[2,2],[1,3]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen vectors are {}".format(values,vectors))
```
## Output:![image](https://github.com/subha2406/EIGENVALUES-AND-EIGENVECTORS/assets/155226504/884bc9c8-d87d-4114-98f4-ef1bdd65d20d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
