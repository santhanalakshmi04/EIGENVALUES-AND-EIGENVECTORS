# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : To find inverse of a matrix using python programming
### Step 2: Import numpy as np.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print result

## Program:
```
DEVELOPED BY : K.SANTHANA LAKSHMI
REFERENCE NUMBER: 212222240091
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/santhanalakshmi04/EIGENVALUES-AND-EIGENVECTORS/assets/119475762/38867e2d-4078-4481-907d-cc0c2c54ee4c)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
