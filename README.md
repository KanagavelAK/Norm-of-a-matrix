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
# 1-Norm of a Matrix
Program to find 1-Norm of a matrix
Developed by : KANAGAVEL A K
RegisterNumber : 212223230096
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: KANAGAVEL A K
RegisterNumber: 212223230096
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix
Program to find infinity norm of a matrix
Developed by : KANAGAVEL A K
RegisterNumber : 212223230096
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-28 132843](https://github.com/KanagavelAK/Norm-of-a-matrix/assets/151514454/3dcd5abf-9718-4724-acd3-8ef1dfbef1d9)

### 2-Norm of a Matrix
![Screenshot 2024-04-28 132900](https://github.com/KanagavelAK/Norm-of-a-matrix/assets/151514454/c8a4b65c-68f3-4f4b-98c8-38000b70c336)

### Infinity Norm of a Matrix
![Screenshot 2024-04-28 132918](https://github.com/KanagavelAK/Norm-of-a-matrix/assets/151514454/1ba9bd6b-dbc6-4f35-b0e3-849fc272f11d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
