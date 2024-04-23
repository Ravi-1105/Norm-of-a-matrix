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

# 1-Norm of a Matrix
```
'''
Program to find 1-norm of a matrix.
Developed by: Ravivarman G S
RegisterNumber: 212223100044
'''
import numpy as np

matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))
```


# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Ravivarman G S
RegisterNumber: 212223100044
'''
import numpy as np

matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))
```

# Infinity Norm of a Matrix
```
'''
Program to find infinity-norm of a matrix.
Developed by: Ravivarman G S
RegisterNumber: 212223100044
'''
import numpy as np

matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))
```



## Output:
### 1-Norm of a Matrix
![image](https://github.com/Ravi-1105/Norm-of-a-matrix/assets/139841688/9d566550-6003-4127-b087-87b762f697c0)


### 2-Norm of a Matrix
![image](https://github.com/Ravi-1105/Norm-of-a-matrix/assets/139841688/ebb8e604-1229-4c25-b8aa-da2611a3aceb)


### Infinity Norm of a Matrix
![image](https://github.com/Ravi-1105/Norm-of-a-matrix/assets/139841688/bffdd0c0-f37a-4f33-9c90-c61e596d6f9c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
