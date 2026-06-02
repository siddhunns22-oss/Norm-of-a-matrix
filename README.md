# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 212225240148
# Developed By: SIDDHARTH N N
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: SIDDAHRTH N N
RegisterNumber: 212225240148 
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
matrix=np.array(eval(input()))
two_matrix = np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))



# Infinity Norm of a Matrix


import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))

```
## Output:
### 1-Norm of a Matrix
<img width="632" height="191" alt="image" src="https://github.com/user-attachments/assets/75e9e471-a2eb-4c3d-8462-bbd56a220e0a" />


### 2-Norm of a Matrix
<img width="652" height="277" alt="image" src="https://github.com/user-attachments/assets/ecf9c030-edba-4762-9eb7-08bad1dee22d" />


### Infinity Norm of a Matrix
<img width="710" height="187" alt="image" src="https://github.com/user-attachments/assets/40e14f8b-9713-4166-ab50-6d42fb3c85a1" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
