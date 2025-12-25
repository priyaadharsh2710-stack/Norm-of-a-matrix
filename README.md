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
# Register No: 25018161
# Developed By: Priyadharshini V

# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,1)
print(norm)


# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print(f"{norm:.2f}")
 


# Infinity Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,np.inf)
print(norm) 



```
## Output:
### 1-Norm of a Matrix
<br><img width="1920" height="1080" alt="Screenshot 2025-12-25 130418" src="https://github.com/user-attachments/assets/513e5718-0640-410f-9db6-1760f6b4485f" />

<br><img width="1920" height="1080" alt="Screenshot 2025-12-25 130432" src="https://github.com/user-attachments/assets/3283568b-1cf6-4609-8a2f-da5aa0331119" />

<br>

### 2-Norm of a Matrix
<br><img width="1920" height="1080" alt="Screenshot 2025-12-25 130443" src="https://github.com/user-attachments/assets/cf7e6f49-e6df-4d59-8d81-4bee56618b92" />

<br><img width="1920" height="1080" alt="Screenshot 2025-12-25 130453" src="https://github.com/user-attachments/assets/7333613d-04eb-46c5-8555-9cf2b8a72f0e" />

<br>

### Infinity Norm of a Matrix
<br><img width="1920" height="1080" alt="Screenshot 2025-12-25 130503" src="https://github.com/user-attachments/assets/acd4bf32-b33f-4bba-b4ad-3827ce67d33c" />

<br><img width="1920" height="1080" alt="Screenshot 2025-12-25 130516" src="https://github.com/user-attachments/assets/ee6d2bda-f2ad-4522-90e2-a07b9b8f1052" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
