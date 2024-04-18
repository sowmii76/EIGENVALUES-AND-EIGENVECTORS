# EIGENVALUES-AND-EIGENVECTORS
## DATE:23.03.2024
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner.
## Algorithm:
### Step1 : 
Importing the Numpy library.
### Step 2: 
Define a given matrix A.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print and end the program.
## Program:
```
#Devoloped by: Sowmiya G
#Registernumber:2305002023
import numpy as np
a=np.array([[2,2],[1,3]])
e,ev=np.linalg.eig(a)
print("the eigen values are",e,"\nthe eigen vectors are\n",ev)
```
## Output:
![image](https://github.com/sowmii76/EIGENVALUES-AND-EIGENVECTORS/assets/146059163/158159c4-d588-4574-85ef-83925c930937)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
