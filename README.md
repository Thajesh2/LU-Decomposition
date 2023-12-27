# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1: Import numpy library using import statement.

Step 2: From scipy package import lu().

Step 3: Get input from user and pass it as an array.

Step 4: Get P, L, U matrix using lu()

Step 5: Print L and U matrix

## Program:
(i) To find the L and U matrix
~~~
developed by : thajesh k
registernumber: 23004042
import numpy as np
import scipy
from scipy.linalg import lu
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)
~~~
(ii) To find the LU Decomposition of a matrix
~~~
developed by : thajesh k
registernumber: 23004042
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A =eval(input())
B =eval(input())
lu,piv= lu_factor(A)
x= lu_solve((lu,piv),B)
print(x)
~~~


## Output:
![Screenshot 2023-12-27 083117](https://github.com/Thajesh2/LU-Decomposition/assets/139841959/758c8e60-8fbc-4c87-9241-134a68e41866)

![Screenshot 2023-12-27 062125](https://github.com/Thajesh2/LU-Decomposition/assets/139841959/0d23933e-ccec-471d-bc0a-e8f2e3123dad)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

