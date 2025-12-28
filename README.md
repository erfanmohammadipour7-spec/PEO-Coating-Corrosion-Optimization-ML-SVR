***

# Machine Learning-Guided Optimization of PEO Coating Parameters

## Overview
This repository contains the source code and dataset for the research paper: **"Machine Learning–Guided Optimization of PEO Coating Parameters Using Support Vector Regression for Enhanced Corrosion Resistance of AZ31 Magnesium Alloy."**

The project employs a data-driven framework to optimize Plasma Electrolytic Oxidation (PEO) process parameters (Current Density and Treatment Time) to minimize corrosion current density ($I_{corr}$) and maximize corrosion potential ($E_{corr}$).

## Key Features
*   **Surrogate Modeling:** Implementation of Support Vector Regression (SVR) to model non-linear electrochemical trends from small datasets.
*   **Model Benchmarking:** Comparative analysis between SVR and Multi-Layer Perceptron (MLP) Neural Networks to justify algorithm selection.
*   **Global Optimization:** Multi-objective optimization using the Differential Evolution algorithm.
*   **Visualization:** High-quality plotting of response surfaces, Pareto fronts, residual analysis, and model comparisons.

## Requirements
*   Python 3.x
*   **Libraries:** `pandas`, `numpy`, `scikit-learn`, `scipy`, `matplotlib`, `seaborn`

## Usage
1.  Place your dataset (`PEO_data.csv`) in the project directory.
2.  Update the `csv_file_path` variable in the script if necessary.
3.  Run the main script:

## Results
The script outputs performance metrics (R², RMSE), generates comparison plots, and prints the predicted optimal processing conditions.
