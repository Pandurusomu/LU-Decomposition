# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np and import lu from scipy.linalg
2. with the help of the np.array take the input from the user
3. creare l,u,p  variables and assign the lu of matrix 
4. Now print the l and u of the matrix
5. end the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Panduru somu
RegisterNumber: 212223240111
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
Lu,piv=lu_factor(A)
X = lu_solve((Lu,piv),B)
print(X)
```

## Output:
![Screenshot 2023-12-30 152501](https://github.com/Pandurusomu/LU-Decomposition/assets/148988619/13a24859-cd73-48d6-8b60-cb50d91f7336)

![image](https://github.com/Pandurusomu/LU-Decomposition/assets/148988619/fdb02da6-a68d-425a-aab4-246060415a31)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

