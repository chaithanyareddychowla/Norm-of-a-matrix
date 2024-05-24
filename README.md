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
# Register No: 22006375
# Developed By: chaithanya.c
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans= np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/chaithanyareddychowla/Norm-of-a-matrix/assets/165985172/612ed6f8-f08d-446b-9d41-2215a9a3ae12)
### 2-Norm of a Matrix
![image](https://github.com/chaithanyareddychowla/Norm-of-a-matrix/assets/165985172/da01f862-2ec0-49d6-95e2-60267090dbe4)
### Infinity Norm of a Matrix
![image](https://github.com/chaithanyareddychowla/Norm-of-a-matrix/assets/165985172/2fd51a1b-da63-4bd6-b2aa-4d791f1a5783)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
