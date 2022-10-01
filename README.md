# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. From scipy.linalg module import the lu function
3. Get inputs from the user and assign the values in np.array()
4. Using the lu() function,we can find the L and U matrix
5. Print the obtained values
6. End the program

## Program:
(i) To find the L and U matrix
```python
Program to find the L and U matrix using LU decomposition
#Developed by: sharangini TK
#RegisterNumber: 22003363

# To print L and U matrix
import numpy as np
from scipy. linalg import lu 
a=eval(input()) 
P, L, U=lu(a) 
print(L)
print(U)
```
## output:
![output](/L%26U.png)
## Result:
 Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.


## AIM:
To write a program to solve a matrix using LU decmposition.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
1. Import the numpy module to use the built-in functions for calculation
2. From scipy.linalg module import the lu_factor and lu_solve functions for calculations
3. Get inputs from the user and assign the values in A and B in np.array()
4. Using the lu_factor(),we can find the LU and pivot
5. Substitute the value in a variable obtained from lu_solved()
6. Print the variable
7. End the program

## Program:
(ii) To find the LU Decomposition of a matrix
```python
Program to solve a matrix using LU decomposition
#Developed by: sharangini TK
#RegisterNumber: 22003363

# To print X matrix (solution to the equations)
import numpy as np
from scipy. linalg import lu_factor, lu_solve
a=eval(input())
b=eval(input())
lu, piv=lu_factor(a)
x=lu_solve((lu, piv),b)
print(x)
```
## Output:
![output](/LUD.png)
## Result:
Thus the program to solve the matrix using LU decomposition is written and verified using python programming.

