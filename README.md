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
<img width="720" height="300" alt="image" src="https://github.com/user-attachments/assets/dcc49b70-7546-4735-af6f-229a9117d047" />

### 2-Norm of a Matrix
<img width="599" height="339" alt="image" src="https://github.com/user-attachments/assets/5c8948df-b58c-4e11-997c-5799170163c5" />

### Infinity Norm of a Matrix
<img width="647" height="264" alt="image" src="https://github.com/user-attachments/assets/4be08623-b065-468b-b83a-9fb797e324b5" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
