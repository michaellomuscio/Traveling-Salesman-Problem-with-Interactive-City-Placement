
# Traveling Salesman Problem with Interactive City Placement

## Overview
This interactive example allows you to place cities on a canvas and then uses a genetic algorithm to solve the Traveling Salesman Problem (TSP) based on the cities you've placed.

## How to Use
- Open `index.html` in a web browser.
- Click on the canvas to place cities.
- Once you've placed all the cities you want, click "Start Optimization" to see the genetic algorithm in action.

## Mechanism
The genetic algorithm optimizes the path using:
- **Selection**: Routes with shorter distances have a higher chance of being selected.
- **Crossover**: Combines two routes to produce a new route.
- **Mutation**: There's a chance to swap two cities in a route to introduce variability.
