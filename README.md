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
#Developed by:Priyadharshini.E 
#RegisterNumber:23012593
import numpy as np
A = ([[1,3],[2,5]])
B = np.array([5,-3])
c = np.linalg.solve(A,B)
print(c)


```
## Output:

<img width="397" alt="image" src="https://github.com/EPriyadharshini/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/144870831/fa9a4850-0a70-4165-9b20-a28b0de4f653">

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

