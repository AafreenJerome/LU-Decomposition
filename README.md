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
Program to find L and U matrix using LU decomposition.
Developed by: Aafreen Jerome
RegisterNumber: 26007104

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to solve a matrix using LU decomposition.
Developed by: Aafreen Jerome
RegisterNumber: 26007104

To print X matrix (solution to the equations)
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x) 
*/
```

## Output:
<img width="1282" height="822" alt="image" src="https://github.com/user-attachments/assets/12fadb2e-6007-44fe-ab58-edd60ca21a9a" />
<img width="852" height="612" alt="image" src="https://github.com/user-attachments/assets/50d2255f-84b9-4081-a238-66fe035544c9" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

