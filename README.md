# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## AIM:
To write a python program to find a solution to a system of linear equations.
## EQUIPMENTS REQUIRED:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## PROGRAM:
```
#Program to find the solution for the given linear equations.
#Developed by: Daksha Subbaian
#RegisterNumber: 23003584
import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
result=np.linalg.solve(A,B)
print(result)
```
## OUTPUT:
![output](/output01.png)

## RESULT: 
Thus the solutions for the linear equations are successfully solved using python program

