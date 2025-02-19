# Step-by-Step Guide: Running and Analyzing the PET Detector Simulation

## Introduction

In this section, you'll learn how to run the Monte Carlo simulation of the novel PET detector and analyze the generated data. We'll guide you through:

1. **Running the Simulation**: Executing the `sim_picopet.py` script to simulate the PET detector's response.
2. **Understanding the Output**: Exploring the generated data files and their significance.
3. **Analyzing Coincidence Events**: Using the provided Jupyter notebook to process and visualize the results.

## 1. Running the Simulation

Assuming you've completed the setup as described in the [Setup](setup.md) section, follow these steps:

1. **Navigate to the Simulation Directory**: Open your terminal or command prompt and change to the directory containing the `sim_picopet.py` script.

   ```bash
   cd path/to/your/simulation/directory


2. **Execute the Simulation Script: Run the simulation by executing**:
    ```python sim_picopet.py

This script sets up the PET detector geometry, defines the radioactive source, and configures the simulation parameters. Upon execution, it will generate output data files containing the simulation results.