# The Ant Colony Optimization Algorithm on Flemish Cities
**Group project for Ugent Mastat course Big Data Algorithms**

**Contributors:** Zaya Lips, Elio Cristianelli, Annabel De Clercq

This project applies the **Ant Colony Optimization (ACO)** algorithm to solve a version of the **Travelin Salesman Problem (TSP)** over a selected set of Flemish cities. The goal of the TSP is to find the shortest route possible that visits each city exactly once and returns to the starting city.

## Structure of the Repository
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

## Requirements for Use
To run the notebook, make sure to have the following Python packages installed:
- numpy
- matplotlib
- networkx
- random (built-in)
- math (built-in)
- itertools (built-in)

