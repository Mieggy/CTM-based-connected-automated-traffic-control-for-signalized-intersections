# Cell transmission model based connected  automated traffic control for signalized intersections

## Description

This repository contains the code for our research paper titled "Cell Transmission Model-based Connected Automated Traffic Control for Signalized Intersections." The study focuses on Connected Automated Flow Control (CAFC) for optimizing traffic management at signalized intersections using Connected Automated Vehicle (CAV) technology. The CAFC strategy transforms the Cell Transmission Model (CTM) into a real-time control framework, improving traffic throughput and reducing computational complexity. Through numerical experiments, we validate the efficiency and adaptability of this approach.

## Features

- Reproduces key experiments from the original paper
- Implements the methodology as described
- Solves the model using Gurobi optimizer
- Compares results with original findings
- Provides analysis and visualization tools

## Usage

### Data Generation

```sh
# Run the data generation notebook
jupyter notebook generate_data.ipynb
```

- The dataset is randomly generated using a uniform distribution.

### Model Training and Optimization

```sh
# Run the model training and solve it using Gurobi
jupyter notebook model.ipynb
```

- The model is formulated as a quadratic programming problem and solved using the Gurobi optimizer.

### Visualization

```sh
# Run the plotting notebook
jupyter notebook plot.ipynb
```

## Data

- The data used in the replication is randomly generated using a uniform distribution.
- Ensure you have access to the required data files before running the experiments.

## Contact

For any questions, reach out via [Yifan.yao@outlook.com](mailto:yifan.yao@outlook.com)
