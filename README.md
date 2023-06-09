# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3.Find the norm of the matrix using np.linalg.norm()
       1. np.linalg.norm(a,1) for 1-Norm
       2. np.linalg.norm(a,2) for 2-Norm
       3. np.linalg.norm(a,np.inf) for Infinity-Norm
4. Print the norm of the matrix in two decimal places.
```
## Program:
```Python
# Register No:212222230073
# Developed By:LATHISH KANNA M
```
# 1-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)
```

# 2-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)
```

# Infinity Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)
```

## Output:
### 1-Norm of a Matrix
![image](https://github.com/lathishlathish/Norm-of-a-matrix/assets/120359170/7d1f1e68-968b-406a-b1c8-ad4a7a08ddad)

### 2-Norm of a Matrix
![image](https://github.com/lathishlathish/Norm-of-a-matrix/assets/120359170/2874256d-8d94-48f3-b312-e413e3bab91c)

### Infinity Norm of a Matrix
![image](https://github.com/lathishlathish/Norm-of-a-matrix/assets/120359170/f3cea680-6161-4f9e-bf09-c63427d66f2c)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
