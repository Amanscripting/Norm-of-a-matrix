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
'''name:Aman Alam
regno:212224240011
'''
import numpy as np
matrix=eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,1)
print("{:2f}".format(norm))
# 2-Norm of a Matrix


'''
Program to find 2-norm of a matrix.
Developed by: Aman Alam
RegisterNumber: 212224240011
'''
import numpy as np
matrix=eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix


'''
name:Aman Alam
regno:212224240011'''

import numpy as np
matrix=eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,np.inf)
print("{:2f}".format(norm))


```
## Output:
### 1-Norm of a Matrix
<img width="617" height="185" alt="image" src="https://github.com/user-attachments/assets/3df73f80-786e-4692-954f-fe05535e8a73" />

### 2-Norm of a Matrix

<img width="474" height="181" alt="Screenshot 2025-10-23 105414" src="https://github.com/user-attachments/assets/c10e88b1-0a80-4127-88a7-c3632ca49daa" />

### Infinity Norm of a Matrix
<img width="557" height="127" alt="Screenshot 2025-10-23 105507" src="https://github.com/user-attachments/assets/0f8e315d-ed62-4fba-bcd9-ed9ae637655a" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
