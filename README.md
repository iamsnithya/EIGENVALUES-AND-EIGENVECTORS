# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the necessary library, numpy, for matrix operations.
### Step 2: Define the given matrix using the numpy.array() method.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:  Display the eigenvalues and eigenvectors using the print() function.

## Program:

    #Program to find the eigen values and eigen vectors.
    #Developed by: NITHYA S
    #RegisterNumber: 212224240106

    import numpy as np

    a = np.array([[2,2],[1,3]])
    values, vectors = np.linalg.eig(a)
    print('Eigen values are {} and Eigen Vectors are {}'.format(values, vectors))

## Output:
![image](https://github.com/user-attachments/assets/50a97222-6d8c-4c8e-b3bf-631107a01b4e)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
