# The Game of Life

## Overview
This Python program offers a simulation of Conway's Game of Life, emphasizing on the 1D version. The simulation unfolds on a pre-defined 200-square board across 400 time steps, examining deterministic and random initial conditions. Additionally, the document delves into the mathematical formulations of fractals, exploring the Sierpinski Triangle and Koch's Flake, shedding light on their intriguing geometric properties and self-replicating patterns.

## Rules
1. If a box has only one living neighbor, the box in the next row (in the same column) lives.
2. If a box has no living neighbors (2 dead neighbors), the box in the next row (in the same column) dies.
3. If a square has 2 living neighbors, the square in the next row (in the same column) dies.

## Solution
The program utilizes Python with libraries such as NumPy and Matplotlib to implement the rules of the Game of Life. It provides visualizations for both deterministic and random initial conditions, showcasing the evolution of live cells over time.

## Usage
1. Import the required libraries: NumPy, Matplotlib.
2. Define the size of the board (e.g., 201 columns and 400 rows).
3. Set initial conditions (deterministic or random).
4. Run the `gameOfLife` function to simulate the game and visualize the results.

# Sierpinski Triangle and Koch's Flake Exploration

## Sierpinski Triangle
1. **Complete Triangles:** The number of complete triangles in iteration k is given by \(N_k = 3^k\).
2. **Area of Each Triangle:** The area of each complete triangle at iteration k is \(A_k = (\frac{1}{4})^k \cdot a_0\).
3. **Total Area:** The total area of the object at iteration k is \(A_{Total}(k) = (\frac{3}{4})^k \cdot a_0\).

## Koch's Flake
1. **Number of Sides:** The number of sides in the object at iteration k is \(N_k = 3 \cdot 4^k\).
2. **Perimeter:** The perimeter of the object at iteration k is \(P_k = P_0 \cdot (\frac{4}{3})^k\).
3. **Area:** The area of the object at iteration k is \(A_k = \frac{3}{4} \cdot (\frac{4}{9})^k \cdot a_0\).
4. **Total Area:** The total area of the Koch Flake at iteration k is \(A_{Total}(k) = \frac{8}{5} \cdot a_0\).

## Limit Analysis
For both the Sierpinski Triangle and Koch's Flake, as k tends to infinity, the total area approaches zero, indicating a diminishing pattern in the fractals' growth.

## Acknowledgments
This program and analysis were inspired by the mathematical exploration of fractals and cellular automata, contributing to the understanding of self-replicating and evolving patterns.