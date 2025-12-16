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
# Register No: 25018334
# Developed By:kanchana P
# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(norm1)

# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,2)
print(f"{norm1:.2f}")




# Infinity Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
inf_norm=np.linalg.norm(A,np.inf)
print(f"{inf_norm:.2f}")




```
## Output:
### 1-Norm of a Matrix
<img width="1340" height="613" alt="Screenshot 2025-12-16 225814" src="https://github.com/user-attachments/assets/78081e16-fc09-4317-bd16-1a6712490367" />
<img width="1340" height="613" alt="Screenshot 2025-12-16 225814" src="https://github.com/user-attachments/assets/edae0525-68d2-49e6-a86b-d24f9e427820" />



### 2-Norm of a Matrix
<img width="1380" height="812" alt="Screenshot 2025-12-16 225828" src="https://github.com/user-attachments/assets/83804aaa-0729-4aab-97d5-77dceba28e44" />
<img width="1453" height="567" alt="Screenshot 2025-12-16 225844" src="https://github.com/user-attachments/assets/da177dd1-705f-4b73-8bd1-3fc6cb5bdf32" />

### Infinity Norm of a Matrix
<img width="1374" height="786" alt="Screenshot 2025-12-16 225858" src="https://github.com/user-attachments/assets/98991369-25de-48e7-8033-0b9500ac1945" />
<img width="1371" height="624" alt="Screenshot 2025-12-16 225909" src="https://github.com/user-attachments/assets/2d4e662b-2e40-4b2b-9a8c-473a98923d85" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
