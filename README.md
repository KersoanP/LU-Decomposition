# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: KERSOAN P
RegisterNumber: 21001501
from scipy.linalg import lu 
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: KERSOAN P
RegisterNumber: 21001501
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,plv=lu_factor(a)
x=lu_solve((lu,plv),b)
print(x)
*/
```

## Output:
![ludecomposition](maths5.png)
![ludecomposition](maths5..png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

