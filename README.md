# EX-05: LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import libraries
2. Get the matrix from the user
3. Find the L and U
4. Print the solution

## Program:
(i) To find the L and U matrix
```
/*
Program to find L and U matrix using LU decomposition.
Developed by: Keerthana Saravanan
RegisterNumber: 23013398

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to solve a matrix using LU decomposition.
Developed by: Keerthana Saravanan
RegisterNumber: 23013398

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
![Screenshot 2023-12-17 171605](https://github.com/KeerthanaaSaravanan/MATH_EX-05LU-Decomposition/assets/145742596/96b61459-39b7-4a02-9db0-5edda43b6431)
![Screenshot 2023-12-17 171614](https://github.com/KeerthanaaSaravanan/MATH_EX-05LU-Decomposition/assets/145742596/61bb68d8-4421-49c3-8eb4-52da4831f158)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

