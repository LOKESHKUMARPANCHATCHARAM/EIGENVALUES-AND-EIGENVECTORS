# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

## Step1 : Import numpy library as np.
## Step 2: Create a matrix using array() function.
## Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4: Get the output and end the program.


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: 
#RegisterNumber:
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
x,y=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(x,y))
```

## Output:
![output](/eigenvalues_and_eigenvector.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
