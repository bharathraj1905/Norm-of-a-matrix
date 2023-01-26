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
# Register No: 22008848
# Developed By: b.barathraj
# 1-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
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
![1 norm](https://user-images.githubusercontent.com/121490575/214919853-45cafa5a-b7c2-48d3-a8ac-ea4bbf1bc1a5.png)


### 2-Norm of a Matrix
![2 norm](https://user-images.githubusercontent.com/121490575/214919908-6e9179ea-8610-403c-8cc1-a59c68ba7fa7.png)


### Infinity Norm of a Matrix
![infinity](https://user-images.githubusercontent.com/121490575/214919977-9bc6e0a5-bd3f-4bcb-99c9-0275ef833ccb.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
