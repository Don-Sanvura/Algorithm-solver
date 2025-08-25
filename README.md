For the project, create a program that solves Linear Programming and Integer Programming Models and then analyses how the changes in an LP’s parameters change the optimal solution. 
The source code must be a visual studio project. Any .NET programming language may be used. The project should build an executable (solve.exe) that is menu driven with the following: 
The program should be able to accept an input text file with the mathematical model and export all results to an output text file. 
Minimum Requirements Criteria 
•	Program should accept a random amount of decision variables. 
•	Program should accept a random amount of constraints. 
•	Use comments with programming. 
•	Programming Best Practices should be implemented. 
Input Text File Criteria 
The first line contains the following, seperated by spaces: 
•	The word max or min, to indicate whether it is a maximization or a minimization problem. 
•	For each decision variable, a operator to represent wheter the objective function coefficient is a negative or positive. 
•	For each decision variable, a number to represent its objective function coefficient. A line for each constraint: 
•	The operator of the technological coefficients for the decision variables, in the same order as in the specification of the objective function in line 1, that represents whether the technological coefficient is negative or positive. 
•	The technological coefficients for the decision variables, in the same order as in the specification of the objective function in line 1. 
•	The relation used in the constraint, with =,<=, or >=, to indicate respectively, an inequality to constraint the constaint right-hand-side. 
•	The right-hand-side of the constraint. 
Sign Restrictions 
•	Sign restriction to be below all the constraints, seperated by a space, +, -, urs, int, bin, in the same order as in the specification of the objective function in line 1. 
Note: The Linear Programming Model or the Integer Programming Model should be entered into the file. Not the canonical forms of the different algorithms respectivly or the Relaxed Linear Programming Model.  
Example of Input File max +2 +3 +3 +5 +2 +4 +11 +8 +6 +14 +10 +10 <=40 bin bin bin bin bin bin 
Tip: Use the above IP in the video and then play around with the values to show all criteria. 
Processing 
Your program should provide you with the option to select which algorithm to use in order to solve the programming model. 
Your program should provide you with options to perform sensitivy analysis operations after the programming model has been solved. 
Programming Model Criteria 
•	Ability to solve normal max Linear Programming Models (specifically the given Knapsack IP). 
•	Ability to solve binary Integer Programming Models (specifically the given Knapsack IP). 
Algorithms to be available 
•	Primal Simplex Algorithm and Revised Primal Simplex Algorithm. 
•	Branch and Bound Simplex Algorithm or Revised Branch and Bound Simplex Algorithm. 
•	Cutting Plane Algorithm or Revised Cutting Plane Algorithm. 
•	Branch and Bound Knapsack algorithm. 
Algorithm Criteria 
•	Display the Canonical Form and solve using the Primal Simplex Algorithm. Display all tableua iterations. 
•	Display the Canonical Form and solve using the Revised Primal Simplex Algorithm. Display all Product Form and Price Out iterations. 
•	Display the Canonical Form and solve using the Branch & Bound Simplex Algorithm. 
o	Backtracking should be implemented. 
o	Program should create all possible sub-problems to branch on. o Program should fathom all possible nodes of sub-problems. o Display all the table iterations of the above mentioned sub-problems. 
o	Best candidate must be displayed. 
