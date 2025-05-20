# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :import the numpy module to use the built-in functions for calculation.
### Step 2:Assign np.array()
### Step 3:Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:end the program

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by:Sandeep S 
#RegisterNumber:212224230239

import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print(f"""Eigen values are {values} and Eigen Vectors are {vectors}""")
~~~
## Output:
![image](https://github.com/user-attachments/assets/f3cf1f40-dbf6-41ac-8dde-53de80f73ca8)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
