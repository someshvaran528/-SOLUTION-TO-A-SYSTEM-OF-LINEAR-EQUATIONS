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
#Developed by: dilip kumar
#RegisterNumber:25017135
import numpy as np
A=[[1,-3],[3,1]]
B=np.array([0,10])
C=np.linalg.solve(A,B)
print(C)

## Output:
<img width="743" height="903" alt="image" src="https://github.com/user-attachments/assets/2801cc7c-3a41-4d53-8188-9cc6fb15511c" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

