# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
	4. End the program.
## Program:
```Python
# Register No:212225100014
# Developed By: Guhan Vasanth A
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))


# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))


```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="437" height="98" alt="image" src="https://github.com/user-attachments/assets/85f9ff34-ec3a-40d8-8632-23a82d50d3e5" />


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="545" height="167" alt="image" src="https://github.com/user-attachments/assets/13ebf98c-1dfe-4f51-9b9a-153e7f5a4f27" />


### Infinity Norm of a Matrix
<br>
<br>
<br>

<img width="1030" height="472" alt="image" src="https://github.com/user-attachments/assets/c13e66ee-44ec-45eb-9f39-cd20500df0ce" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
