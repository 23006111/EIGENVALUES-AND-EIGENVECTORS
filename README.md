# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module for the calculation.
### Step 2:
assign the np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program


## Program:
```
import numpy as np
A=[[2,-3,0],[2,-5,0],[0,0,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)

```

## Output:
![image](https://github.com/23006111/EIGENVALUES-AND-EIGENVECTORS/assets/145981696/687961e8-88eb-4ad7-9c73-45e5744589ba)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
