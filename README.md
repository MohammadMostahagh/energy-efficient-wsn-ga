# Energy-Efficient Routing in Wireless Sensor Networks Using Genetic Algorithm

This repository contains a course project focused on optimizing routing in a heterogeneous Wireless Sensor Network (WSN) using a Genetic Algorithm (GA).

The project investigates energy-efficient routing while considering network delay, residual node energy, population diversity, and the convergence behavior of the genetic algorithm.

## Features

- Simulation of a heterogeneous Wireless Sensor Network
- Genetic representation of routing solutions
- Tournament selection
- Uniform crossover
- Topology-aware mutation
- Elitism and chromosome repair
- Multi-objective fitness evaluation
- Population diversity analysis
- Multiple independent experimental runs
- Parameter sensitivity analysis
- Statistical evaluation and visualization of results

## Project Structure

- `network.py` — Wireless sensor network model
- `chromosome.py` — Chromosome generation and repair
- `fitness.py` — Fitness function and routing evaluation
- `ga.py` — Genetic Algorithm implementation
- `main.py` — Multi-run experiment execution
- `analyze_results.py` — Statistical analysis of experimental results
- `param_sensitivity.py` — Parameter sensitivity experiments
- `plot_results.py` — Visualization of results

The repository also contains CSV experiment outputs and generated plots.

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib

## Experimental Setup

The Genetic Algorithm is evaluated over multiple independent runs using different random seeds. Performance is analyzed based on metrics including:

- Fitness
- Energy consumption
- Routing delay
- Minimum residual energy
- Population diversity
- Convergence behavior

## Sample Results

The repository includes visualizations for:

- Fitness convergence
- Population diversity
- Energy optimization
- Delay optimization
- Residual energy
- Mutation-rate sensitivity
- Population-size sensitivity
- Crossover-rate sensitivity
- Robustness across multiple runs

## Academic Context

This project was originally developed as part of university coursework and is published here as part of my academic and programming portfolio.
