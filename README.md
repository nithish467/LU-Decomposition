# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program 

(i) To find the L and U matrix
## Developed by: NITHISH KUMAR S
## RegisterNumber: 23013506

```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix

## Program to find the LU Decomposition of a matrix.
## Developed by: NITHISH KUMAR S
## RegisterNumber: 23013506
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)

```


## Output:
![image](https://github.com/nithish467/LU-Decomposition/assets/150232274/26d80f22-77c0-470e-aff7-51388d87bb21)
![image](https://github.com/nithish467/LU-Decomposition/assets/150232274/221a4235-8cd8-427d-b98c-6fca1f9096b0)


![image](https://github.com/nithish467/LU-Decomposition/assets/150232274/abb9379f-5a53-4436-93fa-307781cd2f50)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

