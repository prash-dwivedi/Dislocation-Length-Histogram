# Dislocation Length Histogram Script for OVITO

## Overview
This Python script is designed to efficiently extract and analyze dislocation length data from a crystal dislocation analysis file in OVITO. It computes a histogram of dislocation lengths and displays the results directly in OVITO's data inspector.

## Why This Script is Important
Performing Dislocation Analysis (DXA) is often computationally expensive and can consume significant resources, especially when dealing with large datasets or complex simulations. By using this script:
- You can avoid running the DXA analysis repeatedly.
- Save time and computational power.
- Quickly analyze and visualize the distribution of dislocation lengths in your material.

## Features
- Computes a histogram of dislocation lengths from existing DXA data.
- Automatically visualizes the histogram in OVITO's data inspector.
- Helps in studying material deformation mechanisms by providing insights into dislocation behavior.
- 
## Citation

If you use this script in your research, please cite the following articles:

- [DOI: 10.1016/j.jnucmat.2024.155289](https://doi.org/10.1016/j.jnucmat.2024.155289)
- [DOI: 10.1016/j.jnucmat.2024.155042](https://doi.org/10.1016/j.jnucmat.2024.155042)

## Usage
1. Open OVITO and load the dislocation analysis file.
2. Attach this script to the pipeline.
3. View the histogram of dislocation lengths in the data inspector.

## Requirements
- OVITO (Open Visualization Tool)
- Python (for scripting in OVITO)
- NumPy library

## How It Works
The script reads the lengths of dislocation segments from the current data frame, calculates a histogram of these lengths, and creates a DataTable object that is automatically displayed in OVITO.

## License
This project is open-source and available under the MIT license.
