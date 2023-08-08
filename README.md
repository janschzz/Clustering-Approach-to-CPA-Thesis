# A Clustering Approach to Column Type Annotation: Effects of Pre-Clustering

This repository contains the source code and supplementary materials related to my thesis, titled "A Clustering Approach to Column Type Annotation: Effects of Pre-Clustering". The repository consists of two key files detailed below.

## Files Overview

### 1. SemJET
This folder contains two Jupyter Notebooks for the baseline algorithm and the SemJET algorithm. The following steps will guide you to execute the algorithms:

- **Running the Algorithms:** To execute either the baseline or SemJET algorithm, run all the cells from the beginning up to and including the cell marked with `# Execute here`. Execution of this cell will start the chosen algorithm.
- **Dependencies:** Please note that the execution may require specific Python packages. If you encounter any missing dependencies, kindly install them using your preferred package manager (e.g., pip, conda).

### 2. Interval
This file provides a comprehensive study on the derived Interval. Specifically, it offers:

- **Numerical Approximations & Curve Fitting**: Interval derivation.
- **Simulation**: Simulation used in thesis for exploring interval robustness.
- **Mean-Shift Analysis**: Examining the changes in the mean-shift of the near-optimal `k` distribution as Dirichlet parameters increase uniformly.
- **Near-Optimal `k` Density Analysis**: Exploring the probability density of near-optimal `k` across varying underlying data distributions.

All results presented here are consistent with those showcased in the thesis.


## Installation and Setup

### Clone the Repository
You can clone this repository to your local machine using:

git clone https://github.com/janschzz/Clustering-Approach-to-CTA-Thesis.git

### Working with Jupyter Notebooks
If you're unfamiliar with Jupyter Notebooks, you can install Jupyter through pip:

pip install jupyter

Then, navigate to the repository directory and start Jupyter:

jupyter notebook

## Support

If you have any questions or need further clarification on any aspect of this project, please open an issue or contact me directly.

## Author

[Jan Luca Schmelzer](Schmelzj@students.uni-marburg.de)
