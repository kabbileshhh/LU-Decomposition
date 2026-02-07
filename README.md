# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program

## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: KABBILESH.S
#RegisterNumber: 212225240063
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
#Program to solve a matrix using LU decomposition.
#Developed by: KABBILESH.S
#RegisterNumber: 21225240063
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```
## Output:
<img width="1465" height="865" alt="Screenshot 2026-02-07 084119" src="https://github.com/user-attachments/assets/f04e17b6-583b-4534-9d84-214f3295de15" />
<img width="1724" height="741" alt="Screenshot 2026-02-07 084136" src="https://github.com/user-attachments/assets/e6cb7cb5-90fe-4f93-a095-dcf85f682385" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

