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
# Register No:212225240033
# Developed By:DHARSHIN M
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_="{:.2f}".format(ans)
print(norm_)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_="{:.2f}".format(ans)
print(norm_)

```
## Output:
### 1-Norm of a Matrix
<img width="1216" height="696" alt="image" src="https://github.com/user-attachments/assets/f3eb313a-1453-4312-8be5-03c6161ec495" />


### 2-Norm of a Matrix
<img width="1205" height="726" alt="image" src="https://github.com/user-attachments/assets/46cc8fde-cc05-4685-a71a-b8e12f4b64d3" />


### Infinity Norm of a Matrix
<img width="1237" height="706" alt="image" src="https://github.com/user-attachments/assets/a58a8266-2d34-428d-beb0-f6f3edb2c1fd" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
