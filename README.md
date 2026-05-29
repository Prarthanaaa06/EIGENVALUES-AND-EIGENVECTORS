# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1: Import the Library: Bring in the numpy library (specifically alias it as np), which provides high-performance mathematical functions for linear algebra.

## Step 2: Define the Matrix: Create the target 2x2 matrix using np.array([[2, 2], [1, 3]]).

## Step 3:Compute the Values: Pass the matrix into NumPy's built-in linear algebra function, np.linalg.eig(). This function automatically calculates both the eigenvalues and their corresponding normalized eigenvectors.

## Step 4:Display the Output: Print the computed eigenvalues and eigenvectors formatted clearly on the screen.

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: PRARTHANA D
#RegisterNumber: 212225230213

import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix = np.array([[2,2],[1,3]])
eig_val,eig_vec = np.linalg.eig(matrix)

print(f"Eigen values are {eig_val} and Eigen Vectors are {eig_vec}")

## Output:
<img width="1373" height="844" alt="image" src="https://github.com/user-attachments/assets/b76bd333-acdf-4c96-be4b-f2c41b3a7c72" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
