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
# Register No:24901201
# Developed By:NARESH S
```
```
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
```
```
# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
```
```
# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```


## Output:
### 1-Norm of a Matrix

<img width="1194" height="920" alt="image" src="https://github.com/user-attachments/assets/bf9db49d-bc4c-4416-9ef9-62467b42971c" />


### 2-Norm of a Matrix

<img width="1040" height="931" alt="image" src="https://github.com/user-attachments/assets/a8c91a43-a5f9-424e-b589-d22ebc92fb6d" />


### Infinity Norm of a Matrix

<img width="967" height="859" alt="image" src="https://github.com/user-attachments/assets/a4c7ae76-6292-4793-a7a9-47a6ccd00f93" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
