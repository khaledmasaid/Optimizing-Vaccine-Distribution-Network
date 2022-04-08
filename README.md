# Optimizing-Vaccine-Distribution-Network
# Context
As part of Decision Analytics course project, we decided as team to use optimization methods for vaccine distribution, the project is based on the famous Travelling salesman problem. 
# Problem Description and Formulation
We decided to solve this problem on a smaller scale that includes Montreal and surrounding cities.
The objective here was to select optimal distribution routes while minimizing the costse. Please refer to the report for more details including all formulas, decision variables and constraints.

# Results
The figure below displays the locations of vaccine drop-off centers with respect to the departure location (red dot)

<img width="236" alt="image" src="https://user-images.githubusercontent.com/103283892/162528581-f62c6115-b4c6-4138-b289-22cb0beec259.png">

The vaccine distribution model is non-linear and therefore Gurobi was used to generate the optimal solution, figure below displays the optimal routes selected by the model.

<img width="253" alt="image" src="https://user-images.githubusercontent.com/103283892/162528618-1ef85295-6037-4cb3-a794-5bf962e02f8b.png">
