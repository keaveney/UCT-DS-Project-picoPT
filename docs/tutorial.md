# Step-by-Step Guide: Running and Analyzing the PET Detector Simulation

## Introduction

In this section, you'll learn how to run the Monte Carlo simulation of the novel PET detector and analyze the generated data. We'll guide you through:

1. **Running the Simulation**: Executing the `sim_picopet.py` script to simulate the PET detector's response.
2. **Understanding the Output**: Exploring the generated data files and their significance.
3. **Analyzing Coincidence Events**: Using the provided Jupyter notebook to process and visualize the results.

## 1. Running the Simulation

Assuming you've completed the setup as described in the [Setup](setup.md) section, follow these steps:

1. **Navigate to the Simulation Directory**: Open your terminal or command prompt and change to the directory containing the `sim_picopet.py` script.

    ```
    cd path/to/your/simulation/directory
    ```


2. **Execute the Simulation Script: Run the simulation by executing**:

    ```
    python sim_picopet.py
    ```

This script sets up the PET detector geometry, defines the radioactive source, and configures the simulation parameters. Upon execution, it will generate output data files containing the simulation results.


## 2. Understanding the Output

After running the simulation, you'll find several output files in your directory. Key files include:

output.root: A ROOT file containing detailed information about each detected event.
coincidences.txt: A text file listing detected coincidence events, crucial for image reconstruction.
Understanding these files is essential for analyzing the detector's performance and the quality of the simulated PET scan.


## 3. Analyzing Coincidence Events

To analyze the simulation data:

1. **Open the Jupyter Notebook: Launch Jupyter Notebook from your terminal**:
```
jupyter notebook
```
Alternatively you can open notebooks in an IDE, e.g, VSCode

Open the recoCoincidences.ipynb notebook provided with the tutorial files.

2.**Explore the Notebook**: 

The notebook guides you through:
1. **Loading Data**: Reading the coincidences.txt file into a manageable format.
2. **Data Visualization**: Plotting histograms and scatter plots to visualize spatial and energy distributions.
3. **Basic Image Reconstruction**: Applying simple algorithms to reconstruct images from the coincidence data.

Each section includes code snippets and explanations to help you understand the analysis process.

## Next Steps

With the basic simulation and analysis complete, you're encouraged to delve deeper:

Modify Simulation Parameters: Experiment with different detector configurations or source properties in the sim_picopet.py script to observe their impact on the results.
Advanced Analysis: Enhance the Jupyter notebook by implementing more sophisticated image reconstruction techniques or statistical analyses.
For structured exercises and ideas for further exploration, proceed to the Exercises and Explore Further sections.