# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. By using lu(), we can find the Eigen values and Eigen vectors
4. End of Program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: NITESH BHANDARI K
RegisterNumber: 212225240101
ReferenceNumber: 25009039
'''
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
P,l,U = lu(a)
print(l)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: NITESH BHANDARI K 
RegisterNumber: 212225240101
ReferenceNumber: 25009039
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu, pivot = lu_factor(a)
x = lu_solve((lu, pivot), b)
print(x)
```

## Output:
i) Finding L and U Matrix
<img width="1213" height="669" alt="image" src="https://github.com/user-attachments/assets/e2b9a6b3-4596-4f14-b434-e816dee2d0e3" />
<img width="1230" height="660" alt="image" src="https://github.com/user-attachments/assets/157c2be6-e2ee-4292-90ec-b87f37597708" />

ii) Finding the LU Decomposition of a matrix

<img width="1246" height="371" alt="image" src="https://github.com/user-attachments/assets/33ab0e4b-a08a-4ecb-b9cc-9bb14baef7ef" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

