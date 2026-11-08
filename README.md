# Travelling Salesperson Problem: Algorithm Comparison

## Overview

This project explores the Travelling Salesperson Problem (TSP) using two optimisation techniques; Simulated Annealing and Genetic Algorithm.

The objective is to find a short route that visits each city once and returns to the starting city. The project compares the algorithms in terms of route distance, convergence behaviour and execution time.

## Technologies Used

- Python
- Pandas
- Matplotlib
- SciPy
- Jupyter Notebook

## Algorithms Implemented

### 1. Simulated Annealing
- Generates an initial random route.
- Creates neighbouring routes by swapping cities.
- Uses a temperature-based acceptance strategy to explore possible solutions.
- Tracks the best route distance during optimisation.

### 2. Genetic Algorithm
- Creates an initial population of random routes.
- Uses tournament selection to select parent routes.
- Applies crossover and mutation to generate new solutions.
- Tracks the best solution across generations.

## Performance Evaluation

The project compares both algorithms using:

- Best route distance
- Execution time
- Convergence history
- Different problem sizes (10, 20, 30, 40 and 50 cities)
- Statistical comparison using an independent t-test

Visualisations are generated to compare convergence, route distance and execution time.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Htoo10/TSP_Coursework.git
cd TSP_Coursework
```

2. Install the required libraries:

```bash
pip install pandas matplotlib scipy
```

3. Open the notebook:

```bash
jupyter notebook TSP_Coursework.ipynb
```

4. Run the notebook cells in order.

Ensure that `cities.csv` is in the same directory as the notebook.

## Learning Outcomes

- Understanding combinatorial optimisation problems.
- Implementing metaheuristic optimisation algorithms.
- Comparing algorithm performance experimentally.
- Analysing convergence and execution time.
- Presenting results using Python visualisations.
