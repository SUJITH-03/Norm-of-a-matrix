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

'''
NAME : SUJITH A
Register no : 212224230278
'''

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: SUJITH A
RegisterNumber: 212224230278
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)


# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)




```
## Output:
### 1-Norm of a Matrix
<img width="517" height="164" alt="image" src="https://github.com/user-attachments/assets/3e068502-4f5b-414a-a02c-4a34beb9aa1f" />


### 2-Norm of a Matrix
<img width="359" height="182" alt="image" src="https://github.com/user-attachments/assets/39b3fc7d-c093-44a1-bcd9-3c29ddb9c93e" />


### Infinity Norm of a Matrix
<img width="338" height="166" alt="image" src="https://github.com/user-attachments/assets/ba524530-7b71-4415-8711-c3a302d794f7" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
