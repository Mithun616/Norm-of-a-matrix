# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

# 1-Norm of a Matrix
Step 1: Accept the matrix from the user in a suitable format.

Step 2: Convert the input into a NumPy array for matrix operations.


Step 3: Use np.linalg.norm with ord=1 to compute the 1-norm of the matrix.

Step 4: Format the result to two decimal places and print it.

Step 5: End of the program

# 2-Norm of a Matrix
Step 1: Accept the matrix input from the user.

Step 2: Convert the input into a NumPy array.

Step 3: Compute the 2-norm of the matrix using np.linalg.norm with ord=2.

Step 4:  Format the result to two decimal places and display it.

Step 5: End of the program

# Infinity Norm of a Matrix
Step 1: Take the matrix input from the user.

Step2: Convert the input into a NumPy array.

Step 3: Compute the infinity norm of the matrix using np.linalg.norm with ord=np.inf.

Step 4: Format the result to two decimal places and print it.

Step 5: End of the program
 
## Program:
```Python
# Register No:24900789
# Developed By: MITHUN KUMAR G
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-04 220827](https://github.com/user-attachments/assets/c715eb15-7644-4d40-bff4-8577f0393335)

### 2-Norm of a Matrix
![Screenshot 2024-12-04 220845](https://github.com/user-attachments/assets/5d4fe531-8696-4182-8560-a9c5e2c22ec0)

### Infinity Norm of a Matrix
![Screenshot 2024-12-04 220901](https://github.com/user-attachments/assets/8a253285-d3ad-486f-a849-60bb0bb3512b)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
