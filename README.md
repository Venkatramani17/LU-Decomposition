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
Developed by: R VENKATRAMANI  
RegisterNumber: 212225240182
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
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
Developed by: R VENKATRAMANI
RegisterNumber: 212225240182
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
*/
```

## Output:
![lu decomposition]()
<img width="1133" height="760" alt="image" src="https://github.com/user-attachments/assets/db57b86e-671d-4126-9105-ffbd04100f0d" />

<img width="979" height="570" alt="image" src="https://github.com/user-attachments/assets/8bde698f-68a1-45b6-8d5d-756e7baff367" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

