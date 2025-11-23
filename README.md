# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program and import the required library (numpy).
2. Initialize the matrix for which the LU decomposition needs to be found.
3. Apply LU Decomposition.
4. Display the results.

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b66c946b-d1c6-49f2-8635-29549048805d" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5a3f27d0-ce2e-4b07-a855-d7f3240f5c18" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

