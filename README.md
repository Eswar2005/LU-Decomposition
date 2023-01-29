# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.solve(), we can find the solutions.
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Thirukaalathessvarar S
RegisterNumber: 22004529
*/
```
```
/*
import numpy as np from scipy.linalg 
import lu 
a=np.array(eval(input()))
p,l,u=lu(a) 
print(l) 
print(u)
*/
```


(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Thirukaalathessvarar S
RegisterNumber: 22004529
*/
```
```
/*
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![luoutput22](https://user-images.githubusercontent.com/121166390/215308404-2c180a34-1bd2-42a4-8180-2cd9ccbc2aaf.png)

![luputput33](https://user-images.githubusercontent.com/121166390/215308416-6012c0a0-eafb-4d82-8639-faca5a37feff.png)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

