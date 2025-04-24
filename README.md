# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1:Input matrix A and ensure it is square.
### Step 2:Use np.linalg.eig(A) to compute the eigenvalues and eigenvectors.
### Step 3:Eigenvalues are returned as the first result of np.linalg.eig().
### Step 4:Eigenvectors are returned as the second result, with each column representing an eigenvector.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: MARIMUTHU MATHAVAN
#RegisterNumber: 212224230153
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigen_value,eigen_vector=np.linalg.eig(a)
print(f"Eigen values are {eigen_value} and Eigen Vectors are {eigen_vector}")
```
## Output:
![Screenshot (60)](https://github.com/user-attachments/assets/171b1b8c-17da-40d6-95aa-71bde2ea29b3)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
