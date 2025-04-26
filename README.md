# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the required numpy library for matrix operations.
### Step 2: 
Create the matrix using numpy.array().
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the eigenvalues and eigenvectors.

## Program:
``` python
#Program to find the eigen values and eigen vectors.
#Developed by: Rithika R
#RegisterNumber:212224240136

import numpy as np

a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print(f'Eigen values are {values} and Eigen Vectors are {vectors}')
```

## Output:
![image](https://github.com/user-attachments/assets/9d399f26-7b55-4e89-a930-da5d06537116)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
