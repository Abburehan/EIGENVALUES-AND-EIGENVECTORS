# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import necessary libraries in the given program.
### Step 2:
Define and write the given matrix.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the computed eigen values and eigen vectors.

## Program:
```#Program to find the eigen values and eigen vectors.
#Developed by: Abbu Rehan
#RegisterNumber: 23010259
import numpy as np
a=[[2,-3,0],[2,-5,0],[0,0,3]]
values,Vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",Vectors)
```


## Output:
![image](https://github.com/Abburehan/EIGENVALUES-AND-EIGENVECTORS/assets/138849336/6e63a5ca-e00f-447b-8200-6811ca9b182a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
