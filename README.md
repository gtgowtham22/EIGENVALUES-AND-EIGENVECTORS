# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the necessary library (NumPy).
### Step 2:  Define the given square matrix.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalues and eigenvectors.

## Program:
```
import numpy as np
a = np.array([[2, 2], [1, 3]])
values, vectors = np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values, vectors))

```

## Output:
![MATHS AI 4](https://github.com/user-attachments/assets/dea4bff2-4f69-4113-a914-8ba07e0d175e)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
