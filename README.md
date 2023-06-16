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
#Developed by: Karthikeyan R
#RegisterNumber:212222240045
import numpy as np
a =np .array([[1,-3],[3,1]])
b =np .array([0,10])
x =np .linalg.solve(a,b)
print(x)
```

## Output:
![maths ex1  1](https://github.com/karthikeyan-R16/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/119421232/6bd57aef-6000-480e-8d02-daf8a43c3cf8)

## Result
Thus the solutions for the linear equations are successfully solved using python program

