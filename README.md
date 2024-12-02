# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Using numpy and scipy.linalg library to calculate the L and U decomposition.
2. get the input form the user.
3. Using lu_factor() and lu_solve() function to solve the lu decomposition.
4. print the output of the lu decomposition program.
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: M Parani Bala
RegisterNumber: 24900379
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: M Parani Bala
RegisterNumber: 24900379
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
![lu decomposition]()

![Screenshot 2024-11-28 182516](https://github.com/user-attachments/assets/e78bb032-a4b4-46b6-8b9d-a604e859674c)
![Screenshot 2024-11-28 182549](https://github.com/user-attachments/assets/9a70082f-7042-499e-b64c-d0c5e1a8c8b0)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

