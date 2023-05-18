# Travel_sales_man_problem_Random_search
This repository contains implementations of random search algorithms for solving the Traveling Salesman Problem (TSP). The TSP is a well-known optimization problem in computer science, where the goal is to find the shortest possible route that visits a set of cities and returns to the starting city, with each city visited exactly once.

The following random search algorithms are implemented in this repository:
# Nearest Neighbor (NN) Algorithm:
1-Start from a randomly selected city as the current city.                                             
2-Mark the current city as visited.                                                                                                                     
3- Repeat until all cities are visited:                                                                                                                          
        - Find the nearest unvisited city to the current city.                                                               
        - Move to the nearest city.                                         
        - Mark the nearest city as visited.                                     
4- Return to the starting city to complete the tour.                                                                                          

![image](https://github.com/HamsaWahed/Travel_sales_man_problem_Random_search/assets/98246082/c25e2988-07a5-4b98-b5be-eaa95d93b5ec)

# Ant Colony Optimization (ACO) Algorithm:
1-Initialize the pheromone trails on each edge with a small positive value.                                                                                      
2-Create a set of artificial ants, each positioned at a random city.                                                                       
3-Repeat for a specified number of iterations or until convergence:      
    - For each ant, construct a complete tour:                   
        1. At each step, select the next city based on pheromone levels and distance.            
        2. Update the pheromone trails on the chosen edges.                                         
    - Update the global best solution based on the ant with the shortest tour.                           
    - Evaporate the pheromone trails to reduce their intensity.                               
    - Apply pheromone reinforcement to the edges of the global best tour.                     
4. Return the global best tour found.                                                                                      

![image](https://github.com/HamsaWahed/Travel_sales_man_problem_Random_search/assets/98246082/b31f21f8-274f-48e3-b0e3-e16e8547f193)


# Genetic Algorithm (GA):
1-Generate an initial population of candidate solutions.                                                                                                  
2-Repeat for a specified number of generations:                                               
    - Evaluate the fitness of each individual in the population based on the tour length.                                             
    - Select the fittest individuals as parents for the next generation.                                            
    - Create new individuals (offspring) through crossover and mutation operations.                                         
    - Replace the least fit individuals in the population with the offspring.                                     
3-Return the best individual (solution) found.                                                                                                                    

![image](https://github.com/HamsaWahed/Travel_sales_man_problem_Random_search/assets/98246082/9bb11990-c486-4ccc-b01f-aa5e89a50f4b)

These steps provide a high-level overview of the algorithms. Each algorithm may have additional details and variations depending on the specific implementation and problem constraints.
