# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 : Import numpr module.

Step 2: Declare the matrix to a variable.

Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4: Print the Eigen values and Vectors. And End the program.

## Program:

#Program to find the eigen values and eigen vectors.

#Developed by: MOHAMMED HANEEF M

#RegisterNumber:212225040249

import numpy as np

A = np.array([
    [4, 2],
    [2, 4]
])

values, vectors = np.linalg.eig(A)

print(f"Eigen values are {values} and Eigen Vectors are {vectors}")

<img width="1283" height="689" alt="image" src="https://github.com/user-attachments/assets/310d9729-82f2-48dc-addf-18fd6744a82d" />


## Output:


<img width="1293" height="322" alt="image" src="https://github.com/user-attachments/assets/47649844-14cf-476a-80af-161f7bc278aa" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
