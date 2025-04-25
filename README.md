# Travelling Salesman Problem 🚶‍♂️

TSP problem solution using genetic algorithm.

---

This was a university project, done in the team of two, for the course "Nonlinear Programming and Evolutionary Algorithms", taken in the 3rd semester of the Software Engineering and Information Technologies program.

The ``goal`` of the project was to:
- apply the acquired knowledge in evolutionary algorithms,
- solve the TSP problem optimally using a genetic algorithm
#
Technologies used: 
- ``Python``
#
Date: January, 2024.

---

# How does it work? ❓
- loads the coordinates of cities from a file and stores them in a dictionary,
- generates the **initial population** (a set of random city route),
- after that, each route’s total distance is calculated using Euclidean distance and then ranked (**fitness evaluation**),
- generate new populations using:
  - ``selection`` – elitism and roulette wheel to choose parents,
  - ``crossover`` – creates children by combining genes from two parents,
  - ``mutation`` – swaps genes in routes randomly to maintain diversity
- the program stops when the best distance doesn’t improve for 30 iterations (**convergence**).

---

# Using the Application ⚙️

To use this website, follow the next steps:
1) clone this repo,
2) run the program in a Python IDE
