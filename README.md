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
# Register No: P.KEERTHANA
# Developed By: 23011895

# 1-Norm of a Matrix

```
import numpy as np
arr=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,1)
norm="{:.2f}".format(sol)
print(norm)

```

# 2-Norm of a Matrix

```
import numpy as np
a=([[1,2],[3,4]])
b=([[-1, 3],[3, -4],[1, 7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,2)
norm="{:.2f}".format(sol)
print(norm)
```

# Infinity Norm of a Matrix

```
import numpy as np
arr=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(sol)
print(norm)
```
```
## Output:

### 1-Norm of a Matrix
![Alt text](7(i).png)
### 2-Norm of a Matrix
![Alt text](7(ii).png)
### Infinity Norm of a Matrix
![Alt text](7(iii).png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
