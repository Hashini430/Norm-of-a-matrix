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

 1. Get the input matrix using np.array()
 2.  2. Find the 1-norm of the matrix using np.linalg.norm()
 3. Print the norm of the matrix in two decimal places.

    1. Get the input matrix using np.array()   
    2. Find the infinity-norm of the matrix using np.linalg.norm()
    3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:24900728
# Developed By:HASHINI R
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
res=np.linalg.norm(a,1)
print(res)

# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
res=np.linalg.norm(a,2)
print("{:.2f}".format(res))

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
res=np.linalg.norm(a,np.inf)
print("{:.2f}".format(res))

```
## Output:
### 1-Norm of a Matrix
![Alt text](<Screenshot from 2024-12-25 18-49-17.png>)

### 2-Norm of a Matrix
![Alt text](<Screenshot from 2024-12-25 18-49-46.png>)

### Infinity Norm of a Matrix
![Alt text](<Screenshot from 2024-12-25 18-50-17.png>)

## Result
```Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.```
