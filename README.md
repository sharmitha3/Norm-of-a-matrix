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
```
Program to find 1-Norm of a Matrix.
# Register No:23002259
# Developed By:SHARMITHA V
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))
```
# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
RegisterNumber: 23002259
Developed by: SHARMITHA V 
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))
```
# Infinity Norm of a Matrix
```
Program to find  Infinity Norm of a Matrix.
RegisterNumber: 23002259
Developed by: SHARMITHA V 
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/sharmitha3/Norm-of-a-matrix/assets/145974496/f26d8341-2b6a-4ac8-b6b8-8615a6b421f3)

### 2-Norm of a Matrix
![image](https://github.com/sharmitha3/Norm-of-a-matrix/assets/145974496/f2e2bffa-dc25-4ae8-ad89-38ea06d0c0a9)

### Infinity Norm of a Matrix
![image](https://github.com/sharmitha3/Norm-of-a-matrix/assets/145974496/ac84146d-9afd-440a-97e4-ffe9c34719f4)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
