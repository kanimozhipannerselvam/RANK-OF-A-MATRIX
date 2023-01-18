# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.![rank of matrix](https://user-images.githubusercontent.com/119476060/213084291-7d9fbc6a-2443-4d2d-b263-2c1aeecee249.png)

### Step 4: End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: kanimozhi
#RegisterNumber:22002752
import numpy as np
A=np.array([[5,-3,10],[2,2,-3],[-3,-1,5]])
sol =np.linalg.matrix_rank(A)
print(sol)
```
## Output:

![rank of matrix](https://user-images.githubusercontent.com/119476060/213084310-cfa16677-0cda-470f-b56d-75efc585fd7c.png)


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

