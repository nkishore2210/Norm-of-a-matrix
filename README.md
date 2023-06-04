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
# Register No: 212222240049
# Developed By: N.kishore

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

![Screenshot 2023-06-04 135346](https://github.com/nkishore2210/Norm-of-a-matrix/assets/118707090/02e4fa7e-8b4e-4f32-b3e4-8d3e24bc38d4)

### 2-Norm of a Matrix

![Screenshot 2023-06-04 135401](https://github.com/nkishore2210/Norm-of-a-matrix/assets/118707090/2a3912b5-f0e9-4f76-9131-7af5dde95e40)

### Infinity Norm of a Matrix

![Screenshot 2023-06-04 135414](https://github.com/nkishore2210/Norm-of-a-matrix/assets/118707090/e8d40a6f-d8d9-4ef8-b8e5-0282c925ebf9)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
