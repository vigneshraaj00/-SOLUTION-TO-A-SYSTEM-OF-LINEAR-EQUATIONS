# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
#Program to find the solution for the given linear equations.
#Developed by: vignesh raaj s
#RegisterNumber:23005346
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
solution = np.linalg.solve(A,B)
print(solution)
## Output:
![Screenshot 2023-11-29 224855](https://github.com/vigneshraaj00/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/138849113/ccab1ea5-fb8f-4408-9cee-1c6eb7b96039)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

