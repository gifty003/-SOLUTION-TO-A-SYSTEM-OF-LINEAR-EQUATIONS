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
import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
result=np.linalg.solve(a,b)
print(result)
```
## Output:
![image](https://github.com/gifty003/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/145822352/5d969254-873d-459f-81a7-84381d77dc53)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

