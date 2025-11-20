# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS

DATE:18.11.2025

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
<img width="1213" height="822" alt="Screenshot 2025-11-19 104809" src="https://github.com/user-attachments/assets/8105c0c4-4c73-4241-ad6d-139c19ea1287" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

