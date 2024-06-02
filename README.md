# Reinforcement Learning Project

This repository contains solutions for the FrozenLake-v1 and Taxi-v3 environments using Q-learning and Q-table methods. Both environments are loaded from [Gymnasium](https://gymnasium.farama.org/).

## Project Structure
```
RF-learning/
├── frozenlake-v1.ipynb
└── taxi-v3.ipynb
```

- `frozenlake-v1.ipynb`: Solution for the FrozenLake-v1 environment.
- `taxi-v3.ipynb`: Solution for the Taxi-v3 environment.

## Installation

To run the notebooks, you need to have Python installed along with the following packages:

- gymnasium
- numpy
- matplotlib
- Jupyter Notebook
- IPython

You can install these packages using pip:

```sh
pip install gymnasium numpy matplotlib jupyter IPython
```
## Usage

1. Clone the repository:

```
git clone https://github.com/p-abdolmaleki/RF-learning.git
cd RF-learning
```

2. Open the Jupyter Notebook:

```
jupyter notebook
```
3. Open frozenlake-v1.ipynb or taxi-v3.ipynb and run the cells to see the Q-learning solutions for the respective environments.

## Description

### FrozenLake-v1
The FrozenLake-v1 environment consists of a grid where the agent needs to navigate from the start to the goal without falling into holes. The solution uses Q-learning to find the optimal policy for navigating the grid.
### Taxi-v3
The Taxi-v3 environment involves a taxi that needs to pick up and drop off passengers at specified locations. The Q-learning algorithm is used to train the taxi to complete its task efficiently.
### Q-Learning
for more information about q-learning use this [link](https://link.springer.com/content/pdf/10.1007/BF00992698.pdf).
