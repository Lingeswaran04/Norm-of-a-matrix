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
# Register No:212222110022
# Developed By:LINGESWARAN K
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
solu=np.linalg.norm(a,1)
norm="{:.2f}".format(solu)
print(norm)

# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
solu=np.linalg.norm(a,2)
norm="{:.2f}".format(solu)
print(norm)

# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
solu=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(solu)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![maths unit 3 exp 7](https://github.com/Lingeswaran04/Norm-of-a-matrix/assets/119103865/487c4274-ac3d-4876-9175-0b5238f25866)

### 2-Norm of a Matrix
![maths unit 3 exp 7-2 norm](https://github.com/Lingeswaran04/Norm-of-a-matrix/assets/119103865/5de652d1-3a54-4680-a047-e6ce66fd0d18)


### Infinity Norm of a Matrix
![Screenshot 2023-10-04 143356](https://github.com/Lingeswaran04/Norm-of-a-matrix/assets/119103865/1900b3c4-ea27-4f5f-b000-4332cb0e1175)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
