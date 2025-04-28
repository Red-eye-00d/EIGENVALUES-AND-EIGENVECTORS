# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

1. Start the program and import the NumPy library.

2. Define the given matrix as a 2D NumPy array.

3. Use the eig function from NumPy to find the eigenvalues and eigenvectors.

4. Store the eigenvalues and eigenvectors in separate variables.

5. Display the eigenvalues and eigenvectors as output.

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: SUDHARSANAN U    
#RegisterNumber:212224230276

import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```
## Output:
![image](https://github.com/user-attachments/assets/12e9d6af-bafd-4dfd-aeee-4c4222277213)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
