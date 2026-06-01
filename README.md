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
# Register No:212225040382
# Developed By:santhosh sivakumar
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="680" height="292" alt="image" src="https://github.com/user-attachments/assets/7133db36-1905-401b-8b53-f3ae0b0ea1fb" />

### 2-Norm of a Matrix
<img width="568" height="328" alt="image" src="https://github.com/user-attachments/assets/1efd3e82-532e-41f9-922b-75dfce169450" />

### Infinity Norm of a Matrix
<img width="684" height="221" alt="image" src="https://github.com/user-attachments/assets/782dc4e2-3ba6-4b8d-acb4-fb7981a590ab" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
