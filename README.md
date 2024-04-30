# Countdown Game Solver

## Overview
This repository contains a Python implementation of a solver for the Countdown numbers game. The Countdown game involves selecting a set of numbers and using basic arithmetic operations (+, -, *, /) to reach a target number. This solver uses a combination of permutation generation, recursive depth-first search, and optimisation techniques to efficiently find solutions.

## Features
- **Dynamic Number Selection:** Users can specify the number of large numbers (from a set of predefined large numbers) to include in their number set.
- **Recursive Solution Exploration:** Explores all possible combinations of numbers and arithmetic operations to find solutions close to or exactly matching the target number.
- **Pruning of Invalid Operations:** Enhances efficiency by eliminating mathematically impossible operations early in the computation.
- **Performance Metrics:** Measures and reports the time taken to find solutions, providing insights into the computational efficiency.

## How It Works
1. **Setup Game:** Initialises the game by allowing the user to choose how many large numbers to include. The system then randomly selects these along with small numbers to form the set of available numbers.
2. **Generate Solutions:** Using permutations and recursive exploration, the solver attempts all possible combinations of the chosen numbers to reach the target.
3. **Optimise Computations:** Applies optimisation techniques such as pruning invalid operations and potentially using memoization to enhance performance.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- Python 3.6+
- Git (for cloning the repository)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/DaraLenaghan-1/Computational-Theory/blob/main/countdown.ipynb
   ```
2. Navigate to the cloned repository:
   ```bash
   cd Computational-Theory
   ```

### Usage
Run the script from the command line:
```bash
python countdown_solver.py
```
Follow the on-screen prompts to select numbers and view the solution.

## Built With
- [Python](https://www.python.org/) - The programming language used.
- [itertools](https://docs.python.org/3/library/itertools.html) - Additional utilities for efficient looping.

## Authors
- **Dara Lenaghan**
