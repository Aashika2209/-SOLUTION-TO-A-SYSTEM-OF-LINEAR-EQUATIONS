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
#Developed by:Aashika Jain
#RegisterNumber:24900589
import numpy as np
A=np.array([(5,-3,-10),(2,2,-3),(-3,-1,5)])
B=np.array([-9,4,-1])
result=np.linalg.solve(A,B)
print(result)
```  
## Output:
![Screenshot 2024-12-13 061348](https://github.com/user-attachments/assets/826ece6d-8b9e-4821-b591-b6f47f19cb1f)



## Result: 
Thus the solutions for the linear equations are successfully solved using python program

