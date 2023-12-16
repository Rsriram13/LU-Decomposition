# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation.
2. Get the array input from the user.
3. Prepare the lists from the given matrix and assign in np.array().
4. Print thr L U matrix values.
 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: sriram R
RegisterNumber: 23004952
*/
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: sriram R
RegisterNumber: 23004952
*/
from scipy.linalg import lu_factor,lu_solve
# To print X matrix (solution to the equations)

import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
(i) To find the L and U matrix
![output](<Screenshot 2023-12-16 215012.png>)
(ii) To find the LU Decomposition of a matrix
![output](<Screenshot 2023-12-16 213111.png>)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

