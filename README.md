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
```
#Program to find the solution for the given linear equations.
import numpy as np
coefficients = np.array([[1, -3], [3, 1]])
constants = np.array([0, 10])
solution = np.linalg.solve(coefficients, constants)
print("[{:.0f}. {:.0f}.]".format(solution[0],solution[1]))
#Developed by:Tharun V K 
#RegisterNumber:212223230231
```
## Output:
![alt text](<Screenshot 2024-04-10 183347.png>)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

