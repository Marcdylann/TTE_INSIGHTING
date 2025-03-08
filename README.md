# Target Trial Emulation with Clustering

This repository contains an implementation of Target Trial Emulation (TTE) using Python, based on the concepts from epidemiology. The project follows a structured approach to replicating and extending the TTE framework, incorporating machine learning techniques.

## Contents

- **TTE-v1.ipynb** - A Python implementation of the Target Trial Emulation framework, converted from an R-based example.
- **TTE-v2.ipynb** - An extended version of TTE that integrates clustering methods for additional insights.
- **data_censored.csv** - Sample dataset extracted from the original reference.

## Features

- Implements the Target Trial Emulation methodology.
- Uses inverse probability of censoring weights (IPCW) to adjust for biases.
- Expands observational data into a trial-like structure.
- Fits a Marginal Structural Model (MSM) to estimate causal effects.
- Introduces clustering techniques to explore subgroup variations.

## Usage

1. Install the required Python libraries (`pandas`, `numpy`, `sklearn`, `statsmodels`, `matplotlib`).
2. Open the Jupyter notebooks (`TTE-v1.ipynb`, `TTE-v2.ipynb`).
3. Run the notebooks step by step to process the data and generate results.

## References

- Original R-based tutorial: [Target Trial Emulation](https://rpubs.com/alanyang0924/TTE)
- Related literature on causal inference and clustering in machine learning.
