# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

Step1: importing numpy function

Step2: use numpy and sys packages

Step3: use nested loops to loop through each row and column

Step4: end the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: ADITHYA V
RegisterNumber: 23000033
*/

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U

```

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: ADITHYA V
RegisterNumber: 23000033
*/

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print (x)

```

## Output:

(i) To find the L and U matrix

![image](https://github.com/ADITHYA23000033/LU-Decomposition/assets/148514544/1159601b-a1b8-47dc-8b2a-3c50f21f9e10)


(ii) To find the LU Decomposition of a matrix

![image](https://github.com/ADITHYA23000033/LU-Decomposition/assets/148514544/a0e81b86-52e1-458b-9baa-ea0dc7fcfda1)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

