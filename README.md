# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1: 
Import the numpy module to use the built-in function for calculation 
### Step 2: 
Prepare the lists from each equations and assign in np.aaray()
### Step 3:
Using the np.linalg.solve(),we can find the solutions. 
### Step 4: 
Now print the solution and end the program

## Program:
```
import numpy as np
a=np.array( [[1,0,3],[-1,2,-2],[2,3,-1]])
solution=np.linalg.inv(a)
print(solution)
```
## Output:

![image](https://github.com/user-attachments/assets/339611f0-82a7-4fad-8f9e-9623f7514cbf)

## Result:
Thus the inverse of given matrix is successfully solved using python program

