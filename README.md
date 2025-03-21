# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Input the coefficient matrix A and the constant matrix B.
2. Convert the input into a NumPy array.
3. Perform LU decomposition on A to obtain L (lower triangular matrix) and U (upper triangular matrix).
4. Output the solution x.
5. end

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Hariselvan S
RegisterNumber: 212224040103
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
Developed by: Hariselvan S
RegisterNumber:212224040103 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)

```

## Output:
(i)![image](https://github.com/user-attachments/assets/2006fa33-7819-4d99-8172-af78ee331e77)

(ii)![image](https://github.com/user-attachments/assets/7d6b7e14-0d58-4c3d-a937-22615d8de855)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

