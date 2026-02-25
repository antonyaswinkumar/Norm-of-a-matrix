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

'''Program to find 1-Norm of the matrix
Developed by: Antony Aswin Kumar L
Register number: 212225010024

# 1-Norm of a Matrix

##The 1-norm of a matrix (maximum column sum norm) is calculated as the maximum of absolute values of each column

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

##The L2 norm (Euclidean norm) of a vector measures the "length" or "magnitude" of the vector
##or it is the square root of the sum of square of all the elements


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix

##The infinity norm of the matrix,often called the maximum row sum norm,
##it is defined as the maximum sum of the absolute value of elements in each row


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

<img width="1224" height="787" alt="Screenshot 2026-02-25 093647" src="https://github.com/user-attachments/assets/af717f73-d88b-4a08-aa24-6deef0d67943" />



### 2-Norm of a Matrix


<img width="1070" height="837" alt="Screenshot 2026-02-25 093704" src="https://github.com/user-attachments/assets/744918c6-b254-4891-8349-cfcb20a101a3" />


### Infinity Norm of a Matrix

<img width="1018" height="791" alt="Screenshot 2026-02-25 093716" src="https://github.com/user-attachments/assets/223866d0-ba4a-4600-ac8c-938c6e40e206" />


## Result:
Thus the program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places is executed successfully.
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
