## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: lekhashri E
#RegisterNumber:25008477
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:
<img width="1209" height="843" alt="Screenshot 2025-11-27 215417" src="https://github.com/user-attachments/assets/5e66b2eb-ce1f-4b2f-8157-8302c5dd162b" />
<img width="1238" height="237" alt="Screenshot 2025-11-27 215439" src="https://github.com/user-attachments/assets/3d824bb8-1776-4e7e-bccd-4f9c7807a7d7" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
