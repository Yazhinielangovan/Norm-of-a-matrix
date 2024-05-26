## EXPEREIMENT NO.: 07
## DATE : 13.04.2024

# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Developed By: YAZHINI
# Register No: 2305002028
# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
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

![image](https://github.com/Yazhinielangovan/Norm-of-a-matrix/assets/155508323/e1c5987f-1c07-4eff-8975-df5c3895a01f)

### 2-Norm of a Matrix

![image](https://github.com/Yazhinielangovan/Norm-of-a-matrix/assets/155508323/f9ab5227-dd10-43b7-8cc3-01fbb3ad7619)

### Infinity Norm of a Matrix

![image](https://github.com/Yazhinielangovan/Norm-of-a-matrix/assets/155508323/b572a359-d6f3-4ec2-9943-7ed326e4b45d)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
