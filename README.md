# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print' .

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable

4.print the variable 'X'


## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: SUSHMITHA S
RegisterNumber: 212224230282
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: SUSHMITHA S
RegisterNumber: 212224230282
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

## Output:


![Screenshot 2025-04-14 200003](https://github.com/user-attachments/assets/14c0df33-1a8d-478c-994d-a17fd2e87683)


![Screenshot 2025-04-14 200020](https://github.com/user-attachments/assets/f5ef4125-5a13-49e8-b450-91cebfa2f88a)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

