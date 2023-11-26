# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program by import numpy as np.
### Step 2: 
Assign the values equal to a.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the program .
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: GANJI MUNI MADHURI
#RegisterNumber:23002365
import numpy as np
a=[[2,-3,0],[2,-5,0],[0,0,3]]
Values,vectors=np.linalg.eig(a)
print("Eigen values are",Values,"and Eigen Vectors are",vectors)
```

## Output:
![output](/eigen%20values.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
