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
Name:Rabin R
Reg no: 212224230213
```Python
# Register No:
# Developed By:
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
<img width="1337" height="844" alt="Screenshot 2025-09-26 092423" src="https://github.com/user-attachments/assets/6d7f8663-7015-4555-9b65-a9994752772c" />



### 2-Norm of a Matrix
<img width="1270" height="871" alt="Screenshot 2025-09-26 092434" src="https://github.com/user-attachments/assets/1585ba75-ad48-4c92-9c82-be374d5e1473" />


### Infinity Norm of a Matrix
<img width="554" height="404" alt="image" src="https://github.com/user-attachments/assets/4a94f970-0042-40cf-9328-bd8ec27833f9" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
