# The Ant Colony Optimization Algorithm on Flemish Cities
**Group project for Ugent Mastat course Big Data Algorithms**

**Contributors:** Zaya Lips, Elio Cristianelli, Annabel De Clercq

This project applies the **Ant Colony Optimization (ACO)** algorithm to solve a version of the **Traveling Salesman Problem (TSP)** over 30 of the most populated cities all over the world. The goal of the TSP is to find the shortest route possible that visits each city exactly once and returns to the starting city. The distances between the cities take into account the curvature of the Earth.

## Structure of the repository
```
├── .ipynb_checkpoints/                 # Auto-generated Jupyter checkpoint files
│   └── DBA group project ACO-checkpoint.ipynb
│
├── code/                              # Main project code
│   ├── .ipynb_checkpoints/            
│   ├── DBA group project ACO.ipynb    # Main notebook implementing the ACO algorithm
│   └── best_params.json               # File that stores the best performing ACO parameters
│
├── data/                              # Data used in project
│   └── worldcities.csv                
│
└── README.md                          # Project documentation
```

## Requirements for use
To run the notebook, make sure to have the following Python packages installed:
- numpy
- matplotlib
- networkx
- built-in packages random, math, itertools

## How to run the project
1. Copy this repository or download it as a ZIP.
2. Open the `code/DBA group project ACO.ipynb` notebook in Jupyter notebook.
3. Run all cells to simulate the ACO algorithm on the world cities dataset step by step.
4. The notebook will print intermediate results and visualize the final shortest path found.

Optional: The file `best_params.json` contains the best parameters we found while experimenting.

## Credits to original creator
This project builds upon and adapts code from the following repository:

🔗 [https://strikingloo.github.io/ant-colony-optimization-tsp](https://strikingloo.github.io/ant-colony-optimization-tsp)

We modified and extended the code to apply ACO to a global Traveling Salesman Problem using real-world cities.
