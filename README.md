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
# Register No:25006709
# Developed By:Carlton Maximus A
# 1-Norm of a Matrix

# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)


# 2-Norm of a Matrix

# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")


# Infinity Norm of a Matrix


# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)


```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="370" height="533" alt="{1183701D-42E2-4541-8467-92DA9699D2CE}" src="https://github.com/user-attachments/assets/c0825595-086b-4262-ae7d-4229901fb2a1" />


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="358" height="581" alt="{8599A7DE-94AA-462A-B9B3-8693B8CF436A}" src="https://github.com/user-attachments/assets/0627de2d-e0c7-47c2-8df4-68ebb37ec3e8" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="379" height="490" alt="{AF137430-41E1-4AF1-85C2-61362160EDC6}" src="https://github.com/user-attachments/assets/f4f499fe-e6f4-46b3-9ee9-9ced574ef6a1" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
