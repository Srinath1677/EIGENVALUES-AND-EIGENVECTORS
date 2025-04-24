# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculations
### Step 2: 
Prepare the lists from each linear equations ans assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
Program to find the eigen values and eigen vectors.

Developed by: Srinath YG

#RegisterNumber:212224230274
```python
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```

## Output:

![434615830-23147dc6-5abe-44f7-a992-9a9c50bbc005](https://github.com/user-attachments/assets/51a5befc-e9e3-4ddf-9562-fc29cd60195f)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
