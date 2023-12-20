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
# Register No:212223110033
# Developed By:OVIYA P

# 1-Norm of a Matrix :

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix :

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix

![OUTPUT](https://github.com/Oviya24032K6/Norm-of-a-matrix/assets/147139999/52e86d7d-7ed9-473a-905f-5941888a7a12)



### 2-Norm of a Matrix

![OUTPUT](https://github.com/Oviya24032K6/Norm-of-a-matrix/assets/147139999/82ce6e98-8a6e-4ea7-88ec-07613ad5d0bd)


### Infinity Norm of a Matrix

![OUTPUT](https://github.com/Oviya24032K6/Norm-of-a-matrix/assets/147139999/7a7a2226-0220-4bfe-ac00-1d360bfd855d)


## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
