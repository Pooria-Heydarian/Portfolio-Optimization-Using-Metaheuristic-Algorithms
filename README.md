# Portfolio Optimization Using Metaheuristic Algorithms

This repository contains implementations of three metaheuristic algorithms for portfolio optimization: Simulated Annealing (SA), Particle Swarm Optimization (PSO), and Genetic Algorithm (GA). The objective is to find the optimal allocation of assets in a portfolio to maximize returns while minimizing risk.

## Project Structure

- **Portfolio Optimization - SA.ipynb**: This notebook implements the Simulated Annealing algorithm for portfolio optimization. The algorithm iteratively explores the solution space, aiming to find a global optimum by accepting new solutions based on a probabilistic function.

- **Portfolio Optimization - PSO.ipynb**: This notebook contains the Particle Swarm Optimization algorithm. PSO simulates the social behavior of particles (representing portfolios) moving through the solution space, guided by their own experience and that of their neighbors.

- **Portfolio Optimization - GA.ipynb**: This notebook applies the Genetic Algorithm to portfolio optimization. The algorithm uses processes inspired by natural evolution, such as selection, crossover, and mutation, to evolve solutions over generations.

## Data

The algorithms are applied to a dataset of historical stock prices from various companies. The dataset is loaded and processed in each notebook to compute the necessary returns and risks, which are used as inputs to the optimization algorithms.

## Dependencies

Each notebook requires the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`

You can install these dependencies via pip:

```bash
pip install numpy pandas matplotlib
```

## Usage
To use the notebooks:

1. Clone this repository to your local machine.
2. Open any of the .ipynb files in Jupyter Notebook or JupyterLab.
3. Run the cells sequentially to see the optimization process in action.
Each notebook is self-contained and demonstrates the entire workflow, from data loading and preprocessing to the application of the optimization algorithm and visualization of results.

## Optimization Algorithms
### Simulated Annealing (SA)
Simulated Annealing is inspired by the annealing process in metallurgy. The algorithm tries to find the global optimum by probabilistically accepting worse solutions early in the process, with the probability decreasing over time.

### Particle Swarm Optimization (PSO)
PSO is inspired by the social behavior of birds flocking or fish schooling. Each particle in the swarm represents a potential solution, and the particles move through the solution space to find the optimal allocation based on both their own experience and the experiences of their neighbors.

### Genetic Algorithm (GA)
The Genetic Algorithm is inspired by the process of natural selection. It uses a population of solutions that evolve over generations. Selection, crossover, and mutation are applied to create new generations, with the aim of improving the fitness of the solutions over time.

## Conclusion
This project demonstrates the application of three different metaheuristic algorithms to the problem of portfolio optimization. Each method has its strengths and weaknesses, and the choice of algorithm may depend on the specific requirements and constraints of the problem at hand.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.
