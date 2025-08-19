# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: IRSHATH AHAMED.N 
#RegisterNumber: 212224110025
import numpy as np
A = np.array([[2, -3, 0],[2, -5, 0],[0,  0, 3]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")


```

## Output:
<img width="1359" height="801" alt="Screenshot 2025-08-19 095510" src="https://github.com/user-attachments/assets/b6c7d882-cff2-45a9-9a1b-e8e8c349e6b2" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
