# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1. import numpy as np

Step 2: from scipy package import lu

Step 3: get input from the user

Step 4: print result

## Program:
(i) To find the L and U matrix

/*
Program to find the L and U matrix.
Developed by: A.Pugazh sozhan
RegisterNumber: 212224240121
*/
```
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix

/*
Program to find the LU Decomposition of a matrix.
Developed by: A.Pugazh sozhan
RegisterNumber: 212224240121
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![image](https://github.com/user-attachments/assets/896934cb-7b09-44fe-9406-a65c59602d40)

![image](https://github.com/user-attachments/assets/4aeb072e-7bc0-4cea-9af9-db7e8c2ab17f)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

