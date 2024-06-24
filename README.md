# Optimization-for-Vehicle-Routing-Problem-using-Genetic-Algorithms
This repository contains a Python code file and also Jupyter Notebook file that solves the Vehicle Routing Problem (VRP) using Genetic Algorithms. The VRP is a complex combinatorial optimization problem that aims to determine the most efficient routes for a fleet of vehicles to deliver goods to a set of customers.

## Introduction

The Vehicle Routing Problem (VRP) is a combinatorial optimization and integer programming problem which asks "What is the optimal set of routes for a fleet of vehicles to traverse in order to deliver to a given set of customers?" This project uses Genetic Algorithms (GA) to solve the VRP, aiming to minimize the total distance traveled and ensure balanced load distribution among vehicles.

## Installation

Make sure that your system has the following packages installed -- numpy, matplotlib and deap
If not installed, you can install these by running the following command in your command prompt

    ```bash
    pip install numpy matplotlib deap
    ```
## Features

- **Random Location Generation**: Generates random coordinates for a specified number of locations.
- **Genetic Algorithm Implementation**: Uses selection, crossover, and mutation operations to evolve solutions.
- **Multiple Vehicles Support**: Balances the load among a specified number of vehicles.
- **Distance and Balance Optimization**: Minimizes total distance traveled and ensures balanced load distribution using a penalty for imbalance.
- **Visualization**: Plots the routes of the vehicles, showing the path each vehicle takes from the depot to the locations and back.
