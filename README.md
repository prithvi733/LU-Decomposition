# Ex - no5 LU-Decomposition
# Date:

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'



## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by:V.Prithviraj
RegisterNumber:212222100038
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by:V.Prithviraj
RegisterNumber:212222100038
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu,piv) , b)
print(x) 

```

## Output:

![Screenshot 2024-10-26 103249](https://github.com/user-attachments/assets/aa584b95-d22c-49f0-9905-3ba48b5ba780)

![Screenshot 2024-10-26 103302](https://github.com/user-attachments/assets/19237717-f421-4fbf-bb6f-8377c55e7e7c)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

