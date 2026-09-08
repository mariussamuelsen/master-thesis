# Stress-Testing Conformal Prediction Intervals

Master’s thesis: **Empirical Coverage and Efficiency Across Conditional Volatility Regimes in Tree-Based Brent Oil Forecasting**.

## Overview

This thesis investigates how elevated conditional volatility affects the coverage and efficiency of conformal prediction intervals for next-day Brent crude oil prices.

The analysis compares prediction intervals across stress and non-stress periods, evaluating empirical coverage, interval width, and the Winkler score at a nominal coverage level of 90%.

## Methods

- **Forecasting models:** Decision Tree, Random Forest, LightGBM, and XGBoost.
- **Conformal methods:** Split Conformal Prediction, EnbPI, and Adaptive Conformal Inference (ACI).
- **Stress identification:** Rolling return volatility and GARCH(1,1) conditional volatility.

## Repository contents

| File | Description |
|---|---|
| `MasterThesis.pdf` | Full thesis |
| `(2)Final_Notebook.ipynb` | Final Python analysis notebook |
| `brent_exogenoustechnical_stress2.csv` | Dataset for the analysis |

## Running the analysis

The analysis dataset is included in this repository. To run the notebook, install the required Python packages and update any local file paths to match your setup.

A complete environment specification and step-by-step execution instructions are not yet included.
