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
# Register No:212223240120
# Developed By:Pragadeeswaran L
# 1-Norm of a Matrix:

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,1)
print(f"{two_matrix:.2f}")

# 2-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print(f"{two_matrix:.2f}")

# Infinity Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,np.inf)
print(f"{two_matrix:.2f}")

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-07 110457](https://github.com/Pragadeeswaran-bit/Norm-of-a-matrix/assets/147473828/fe448298-ca63-4f0a-91ae-5c450c57c5d9)

### 2-Norm of a Matrix
![Screenshot 2024-05-07 110603](https://github.com/Pragadeeswaran-bit/Norm-of-a-matrix/assets/147473828/7b4c5e60-5ed6-4fb2-8a6c-dfa7395bc667)

### Infinity Norm of a Matrix
![Screenshot 2024-05-07 110625](https://github.com/Pragadeeswaran-bit/Norm-of-a-matrix/assets/147473828/d954ce14-2abc-4c81-b8b7-29ff708f468c)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
