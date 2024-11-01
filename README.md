# CI2024_lab2

# TSP Project - Traveling Salesman Problem

I used various approaches to solve the Traveling Salesman Problem. Each method has specific advantages and performs better in certain scenarios. Below is a brief description of each implemented algorithm. Each algorithm can be run separately and independently.

## Algorithms

### 1. **Greedy**
   - A simple approach that constructs a path by choosing the nearest unvisited city each time. It’s fast but tends to produce suboptimal routes.

### 2. **Greedy + 2-opt**
   - Extends the Greedy approach by applying the 2-opt optimization, which improves the path by swapping pairs of edges. This method reduces the overall cost compared to Greedy alone.

### 3. **Lin-Kernighan**
   - An advanced heuristic algorithm that makes multiple modifications to the path to minimize the total length. It is one of the best-performing algorithms for the TSP, balancing efficiency and speed.

### 4. **Genetic Algorithm**
   - Simulates natural evolution to explore multiple solutions. It includes crossover and mutation stages, with a mutation rate adjustment mechanism to avoid premature convergence. Note that this algorithm requires a longer runtime, and the parameters (e.g., num_generation, population size) should be adjusted depending on the number of cities to optimize performance.
