# Metaheuristic-Algorithms-to-Optimize-Travelling-Salesman-Problem
Metaheuristic-Algorithms-to-Optimize-Travelling-Salesman-Problem

ASSIGNMENT 1
Apply Simulated Annealing (SA) and Tabu Search (TS) algorithms on the TSP. The detailed information is given below:

Coding:

Use “berlin52.tsp” problem instance.
Use the following parameters for SA and TS.
For SA
Initial T = 100
Cooling function: T  T * 0.999
Stopping criteria: T = 0.001
For TS
Max iterations = 10000 
Tabu list size or recency upper bound = 100 

For TS, you decide on how you want to construct your tabu list. Remember, the easier the better.
Choose your own move for neighbourhood search: 
2-opt
Nearest neighbour
Swap
Insert 
It can be a combination of these, as well. 
Yet, apply the same neighbourhood search in both algorithms.
