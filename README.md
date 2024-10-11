# Norm of a matrix
# EXP - 7 
# Date : 
## Aim :
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.

## Program:
```Python
# Developed By: Saravanan C 
# Register No: 212222110041

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Exp-07 CR Norm of a matrix 1](https://github.com/user-attachments/assets/04c5a8d0-1256-4ee2-8a8a-23878dfb3dc3)
### 2-Norm of a Matrix
![Exp-07 CR Norm of a matrix 2](https://github.com/user-attachments/assets/fb798e8f-5a1d-4f93-893e-0b2283c05119)
### Infinity Norm of a Matrix
![Exp-07 CR Norm of a matrix 3](https://github.com/user-attachments/assets/e53aa65a-cd1b-4c3d-b1bb-5307a8dd4344)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
