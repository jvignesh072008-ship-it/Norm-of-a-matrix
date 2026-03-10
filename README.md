# Norm of a matrix

## Aim

To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:

1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner.

## Algorithm:

	1. Get the input matrix using np.array()   
    2. Find the 1-norm,2-norm and infinity norm of the matrix using np.linalg.norm() 
	3. Print the norm of the matrix in two decimal places.
	
## Program:

```
# Register No: 212225230297
# Developed By: VIGNESH J
# 1-Norm of a Matrix:-

a = eval(input())
from numpy.linalg import norm
print(f"{norm(a,1):.2f}")

# 2-Norm of a Matrix:-

from numpy.linalg import norm
a = eval(input())
print(f"{norm(a,2):.2f}")


# Infinity Norm of a Matrix:-

from numpy.linalg import norm
import numpy as np
a = eval(input())
print(f"{norm(a,np.inf):.2f}")

```
## Output:

### 1-Norm of a Matrix
<img width="958" height="797" alt="image" src="https://github.com/user-attachments/assets/8a94d67a-06bc-4861-bf93-f4b5504100a0" />

### 2-Norm of a Matrix
<img width="609" height="863" alt="image" src="https://github.com/user-attachments/assets/a2b40699-86fd-47e8-b8c7-f1c035ff4541" />

### Infinity Norm of a Matrix
<img width="752" height="854" alt="image" src="https://github.com/user-attachments/assets/6153aaba-4d7e-4b57-8734-ea69674c0480" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
