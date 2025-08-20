# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import NumPy library.
### Step 2: 
Define the matrix for which eigenvalues and eigenvectors are required.
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the results.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: DHANUSH M D
#RegisterNumber: 212224100011

import numpy as np

A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])

values , vector = np.linalg.eig(A)

print("Eigen values are",values,"and Eigen Vectors are",vector)
```
## Output:
<img width="1324" height="819" alt="image" src="https://github.com/user-attachments/assets/04d89677-1fc3-4c49-862c-65aad570cc80" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
