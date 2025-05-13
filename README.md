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
# Register No:21222423097
# Developed By:Irfan khan.N 

# 1-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)

# 2-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print(f"{result:.2f}")

# Infinity Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print(f"{result:.2f}")
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/f781392a-2c97-41e8-a8d5-c4b14e8ac148)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/9f3ede72-ca67-4a86-b059-378f80020c30)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/b386fb0d-69cf-4254-aaaa-499fa88d1902)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
