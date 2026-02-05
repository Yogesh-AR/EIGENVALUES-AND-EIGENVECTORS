# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library.
### Step 2: Define the square matrix.
### Step 3: Apply the NumPy function to compute the eigenvalues and eigenvectors.
### Step 4: Display the eigenvalues and the corresponding eigenvectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: YOGESH A R 
#RegisterNumber: 212225230312

import numpy as np
x=np.array([[4,2],[2,4]])
val,vector=np.linalg.eig(x)
print(f"Eigen values are {val} and Eigen Vectors are {vector}" )
```
## Output:

<img width="1366" height="803" alt="image" src="https://github.com/user-attachments/assets/609254bf-f9a9-4bf0-87e9-e815248f995e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
