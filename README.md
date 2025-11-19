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

import numpy as np
A = np.array([[1, 3], [2, 5]])
B = np.array([5, -3])
solution = np.linalg.solve(A, B)
print(solution)

## Output:
<img width="1920" height="1080" alt="Screenshot (72)" src="https://github.com/user-attachments/assets/4f60b6ed-acea-44c6-bbf6-1302275fcbc8" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

