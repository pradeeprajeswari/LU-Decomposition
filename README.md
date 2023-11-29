# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## (i)
## STEP1:
prompt the user to enter a matrix and convert the input to a numpy array

## STEP2:
Use the LU decomposition function (LU) on the input matrix 

## STEP3:
Retrieve the permutation matrix (P) lower triangular matrix (L), upper triangular matrix (U).

## STEP4:
Display the lower traingular matrix (L) and upper triangular matrix (U).

## (ii)
## STEP1:
Convert the input to numpy arrays (A and B)

## STEP2:
Use the lu_factor function to compute the LU factorizartion of matrix A. Get a factorization result (result) that is needed for solvimg linear systems.

## STEP3:
Apply the lu_solve function using the LU factorization result (result) and the constant vector B.

## STEP4:
Obtain the solution to a linear solution and display the solution to the linear solution.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: PRADEEP.E
RegisterNumber: 23013416

from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:PRADEEP.E 
RegisterNumber: 23013416

from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
*/
```

## Output:
![lu decomposition]()
![lu decomposition1](https://github.com/pradeeprajeswari/LU-Decomposition/assets/145743112/49d719e9-fc99-423e-b060-9085fa143486)
![lu decomposition2](https://github.com/pradeeprajeswari/LU-Decomposition/assets/145743112/d7008628-d873-4258-a9a2-8d14e41bfe11)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

