## DATE:
## EXN0:05 LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
### (i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: MONISH N
RegisterNumber: 212223240097
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
## (ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: MONISH N
RegisterNumber: 212223240097
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output 01:
![Screenshot 2024-09-27 204325](https://github.com/user-attachments/assets/d9bc33d3-d155-4b6d-8099-5fe85e8318f5)

## Output 02:
![Screenshot 2024-09-27 204508](https://github.com/user-attachments/assets/a4bbd16e-59b1-4939-afcc-5a2a5e4a4465)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

