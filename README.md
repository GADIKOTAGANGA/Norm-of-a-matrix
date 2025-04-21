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
# Register No:G.Ganga devi
# Developed By:212224240042
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Ganga devi
RegisterNumber: 212224240042
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)




# Infinity Norm of a Matrix
'''
program to find 2-norm of a matrix.
Developed by: Ganga devi
Register Number:212224240042
'''
import numpy as np
mat=np.array(eval(input()))
norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))





```
## Output:
### 1-Norm of a Matrix

![Screenshot (182)](https://github.com/user-attachments/assets/806831d7-8e49-415f-b3ba-96d4c328d560)

### 2-Norm of a Matrix


![Screenshot (183)](https://github.com/user-attachments/assets/384131a1-877c-4b8b-a275-6f246cb3f686)

### Infinity Norm of a Matrix

![Screenshot (191)](https://github.com/user-attachments/assets/a9408ae7-4638-4198-b62a-7c1291e8e9e3)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
