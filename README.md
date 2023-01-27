# Norm of a matrix
## Aim
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
# Developed By: C Saravanan
# Register No: 22008175

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
![image](https://user-images.githubusercontent.com/121395849/215159205-369da4eb-ed80-47d0-b4d9-55e3ee5105b3.png)
### 2-Norm of a Matrix
![image](https://user-images.githubusercontent.com/121395849/215159267-d1a15f49-a066-4f7f-8ba7-0196a98a3318.png)
### Infinity Norm of a Matrix
![image](https://user-images.githubusercontent.com/121395849/215159310-41f58fa2-e367-49b5-9e3f-1480d951a15f.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
