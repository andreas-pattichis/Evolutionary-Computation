# Evolutionary Computation

## Introduction
This project explores the effects of selection pressure, fitness scaling, mutation rates, and the use of memetic algorithms in genetic algorithms (GAs).

## Project Overview
### Genetic Algorithms
- **Fitness Functions**: Multiple fitness functions were tested to observe how they influence selection pressure.
- **Selection Pressure Analysis**: Studied the impact of fitness scaling on the probability of selection and overall selection pressure.

### (1+1)-GA for Binary Problems
- **Algorithm Characteristics**: Utilized a mutation probability of 1/100 and ran simulations over 1500 generations.
- **Experimental Setup**: Comparisons between original and modified GA to assess the role of selection in achieving high fitness scores.

### Exploration vs. Exploitation
- **Parameter Analysis**: Investigated how the mutation rate affects the balance between exploration (genetic diversity) and exploitation (convergence on solutions).
- **Population Diversity**: Examined how different mutation rates impact the diversity within the population over generations.

### Memetic Algorithms
- **TSP Optimization**: Applied a memetic algorithm (MA) with a 2-opt local search to solve the Traveling Salesman Problem (TSP).
- **Comparison with Simple EA**: Evaluated the performance improvement of MA over a standard evolutionary algorithm (EA).

## Results and Analysis
### Fitness Function and Selection Pressure
- **Selection Probabilities**: Calculated and visualized the selection probabilities under different fitness functions to understand how they affect selection pressure.

### Role of Selection in GAs
- **Performance Analysis**: Demonstrated the necessity of selection in GAs through comparative performance analysis of original and modified (1+1)-GA.

### Exploration vs. Exploitation
- **Mutation Rate Impact**: Detailed the outcomes of varying mutation rates on algorithm performance and population diversity.
- **Optimal Mutation Rates**: Identified optimal mutation rates that balance exploration and exploitation to achieve efficient convergence.

### Memetic Algorithms
- **Performance Enhancement**: Showcased how integrating a local search into GAs can significantly improve the optimization capabilities, particularly for complex problems like the TSP.

## Visualizations
- **Figures and Charts**: Includes pie charts, line graphs, and bar charts to represent algorithm performance, selection probabilities, and genetic diversity.
