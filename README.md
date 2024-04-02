# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Import numpy as np
### Step 2:
From scipy.linalg import lu
### Step 3:
Get the inputs
### Step 4:
Print the values and end the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Vidhiya Lakshmi S
RegisterNumber: 212223230238

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
Program to find the LU Decomposition of a matrix.
Developed by: Vidhiya Lakshmi S
RegisterNumber: 212223230238

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

*/
```

## Output

(i) To find the L and U matrix

![Screenshot 2024-04-02 191701](https://github.com/AkilaMohan/LU-Decomposition/assets/87062069/155a0aed-ed8a-43a9-a0ce-b5bcae822cc5)

(ii) To find the LU Decomposition of a matrix

![Screenshot 2024-04-02 191715](https://github.com/AkilaMohan/LU-Decomposition/assets/87062069/054839a1-e67c-440a-8d24-a45e12519efc)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

