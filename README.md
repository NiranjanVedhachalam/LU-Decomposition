# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Import NumPy and LU decomposition function from SciPy.
2. Take matrix input from the user and convert it into a NumPy array.
3. Perform LU decomposition on the matrix to get P, L, and U.
4. Extract and store the L (lower triangular) and U (upper triangular) matrices.
5. Print the L and U matrices as output.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Niranjan V
RegisterNumber: 212224110042
'''
import  numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Niranjan V
RegisterNumber: 212224110024
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
L,P=lu_factor(a)
x=lu_solve((L,P),b)
print(x)
```

## Output:
(i) To find the L and U matrix

<img width="1459" height="975" alt="Screenshot 2025-08-28 092916" src="https://github.com/user-attachments/assets/93d55590-5c63-4f7f-a3a3-f057dcf6f31d" />

(ii) To find the LU Decomposition of a matrix

<img width="1446" height="850" alt="Screenshot 2025-08-28 092933" src="https://github.com/user-attachments/assets/55583c11-5fc9-4ca0-9904-53549906d725" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

