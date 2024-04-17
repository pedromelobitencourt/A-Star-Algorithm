# A* Algorithm for Finding the Best Path and Minimum Cost from a Source City to Destination (Bucareste)

This repository contains a Jupyter Notebook implementing the A* algorithm to find the best path and minimum cost from a source city to the destination city, Bucareste (Bucharest). The implementation is part of an exercise for an AI course at The Federal Center for Technological Education of Minas Gerais (CEFET-MG).

## Files

- **a_star.ipynb**: This Jupyter Notebook contains the implementation of the A* algorithm.
- **Grafo.txt**: This file represents the edges between cities, where each line contains information about a connection from one city to another with its corresponding weight (distance).
- **Heuristica.txt**: This file contains heuristics for each city, representing the straight-line distance between each city and Bucareste.

## How to Use

1. Clone this repository to your local machine:

```bash
git clone https://github.com/pedromelobitencourt/A-Star-Algorithm.git
```

2. Install Jupyter Notebook if you haven't already:

```
pip install notebook
```

3. Open the astar_algorithm.ipynb notebook and execute the cells to run the A* algorithm.


## Usage Notes

* Ensure that the "Grafo.txt" and "Heuristica.txt" files are in the same directory as the notebook for proper execution.

* Modify the source city as needed in the notebook.

* The A* algorithm will compute the best path and minimum cost to reach Bucareste from the given source city.


### License

This project is licensed under the MIT License