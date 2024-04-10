# EIGENVALUES-AND-EIGENVECTORS
## NAME : V RAKSHA DHARANIKA
## REF.NO: 212223230167
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: V RAKSHA DHARANIKA
#RegisterNumber:212223230167

import numpy as np
A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values, vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Screenshot (114)](https://github.com/rakshadharanika/EIGENVALUES-AND-EIGENVECTORS/assets/149348380/10b3ca1e-cf9b-4152-8cef-4317f4acce26)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
