# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array() 
### Step 3: 
Using the np.linalg.inv(), we can find the rank of the given matrix.
### Step 4: 
End the program

## Program:
```
import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
result=np.linalg.inv(A)
print(result)
```

## Output:
![inversermatrix](https://user-images.githubusercontent.com/118447015/209442676-cbc46a20-fd82-4f57-a9a2-bdfc5ed5a3ab.png)



## Result:
Thus the inverse of given matrix is successfully solved using python program

