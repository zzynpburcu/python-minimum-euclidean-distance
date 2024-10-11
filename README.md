# Minimum Euclidean Distance Calculation

This project demonstrates the calculation of the **Minimum Euclidean Distance** between points in a 2D space using Python. The task involves defining points, writing a function to compute the Euclidean distance between two points, and using loops to find the minimum distance between all pairs of points.

## Table of Contents

- [Introduction](#introduction)
- [Task Description](#task-description)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [License](#license)

## Introduction

Euclidean distance is the straight-line distance between two points in Euclidean space. The formula used to calculate this distance in a 2D plane between two points \((x₁, y₁)\) and \((x₂, y₂)\) is:

\[
d = \sqrt{(x₂ - x₁)^2 + (y₂ - y₁)^2}
\]

This project computes the minimum Euclidean distance between a set of points by calculating the distance for all possible point pairs and finding the smallest value.

## Task Description

You need to write a Python program that:

1. **Defines a List of Points:**
   - Create a list called `points` that contains tuples representing 2D points. Each tuple should consist of an `(x, y)` coordinate. For example: `points = [(x₁, y₁), (x₂, y₂), ...]`.

2. **Writes a Function to Calculate Euclidean Distance:**
   - Define a function `euclideanDistance(point1, point2)` that takes two tuples as input (each representing a point) and returns the Euclidean distance between the two points using the formula above.

3. **Calculates the Distances:**
   - Use a loop to iterate through the `points` list and calculate the Euclidean distance between each pair of points.
   - Store these distances in a list called `distances`.

4. **Finds the Minimum Distance:**
   - Find the minimum distance from the `distances` list and print the result.

## Requirements

Before running the notebook, make sure you have the following installed:

- Python 3.x
- Jupyter Notebook

You can install the required libraries by running:

```bash
pip install notebook
```

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/zzynpburcu/python-minimum-euclidean-distance.git
   ```

2. Navigate to the project directory:

   ```bash
   cd python-minimum-euclidean-distance
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Select the `minimum_euclidean_distance.ipynb` file to start working on the task.

## Usage

1. Open the notebook in Jupyter.
2. Define the list of points in the `points` variable.
3. Run the `euclideanDistance` function, which calculates the Euclidean distance between two points.
4. Run the loop to calculate the distances between all point pairs.
5. The notebook will output the minimum Euclidean distance between the points.

## Example

Given the following points in 2D space:

```python
points = [(1, 2), (4, 6), (5, 2), (9, 8)]
```

The program will calculate the Euclidean distances between all point pairs and print the smallest distance.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
