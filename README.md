# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Input the matrix 
### Step 2: Check properties
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:Output results 

## Program:
```python
import numpy as np

A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])

values,vectors=np.linalg.eig(A)

print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:

<img width="1257" height="758" alt="Screenshot 2026-01-30 170144" src="https://github.com/user-attachments/assets/f19b84b8-c1c2-4fd7-9127-c5c0dc1c7e10" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
