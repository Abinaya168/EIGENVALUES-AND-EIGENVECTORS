# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Start the program.

Step 2: Import the NumPy library using import numpy as np.

Step 3: Get the elements of the matrix as input from the user.

Step 4: Using the np.linalg.eig() function, we can find the eigenvalues and eigenvectors of the given matrix.

Step 5: Display the eigenvalues and eigenvectors.

Step 6: Stop the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Abinaya P
#RegisterNumber:212225230003

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a= np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```

## Output:
<img width="1810" height="897" alt="Screenshot 2026-11-21 103802" src="https://github.com/user-attachments/assets/da4b8f66-992d-48f6-b6b9-9b7d3c329588" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
