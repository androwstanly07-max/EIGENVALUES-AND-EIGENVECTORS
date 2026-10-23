# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
 ### step 1: Import the numpy module to use the built-in functions for calculation
### Step 2:Prepare the lists from each linear equations and assign in np.array()
### Step 3:Using the np.linalg.solve(), we can find the solutions.
### Step 4:End the prograM
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[4,2],[2,4]])
values,Vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))
```
## Output:
<img width="1903" height="914" alt="Screenshot 2026-10-13 231152" src="https://github.com/user-attachments/assets/78ddc7f7-1139-4ba0-a50b-6d19b315c759" />
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
