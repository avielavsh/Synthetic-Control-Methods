# Financial Data Analysis with Dynamic Bayesian Synthetic Control (DBSC)

## Overview

This Jupyter Notebook applies **Dynamic Bayesian Synthetic Control (DBSC)** methods for **factor investing analysis** using **Bayesian Dynamic Models**. It integrates causal inference techniques to assess time-varying treatment effects, improving financial decision-making and policy analysis.

## Features

- **Synthetic Control Methods (SCM):** Used for evaluating causal impacts in financial settings.
- **Dynamic Bayesian Modeling:** Enhances SCM by integrating Bayesian priors and time-series assumptions.
- **Financial Data Analysis:** Analyzes high-frequency financial datasets.
- **Kalman Filtering & MCMC Estimation:** Estimates time-varying relationships for improved accuracy.
- **Visualization Tools:** Uses Plotly and Matplotlib for dynamic trend analysis.

## Requirements

Ensure you have the following Python libraries installed before running the notebook:

```bash
pip install plotly pykalman pymc3 statsmodels scipy pandas numpy matplotlib scikit-learn
```

## Installation & Usage

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Mount your Google Drive and ensure the dataset (`Financial Data.csv`) is placed in the correct directory.
3. Run the cells step by step to analyze and visualize the data.

## Dataset

The notebook expects a CSV file named `Financial Data.csv` stored in Google Drive under:

```
/content/drive/MyDrive/Synthetic Control Methods/data
```

Ensure the file is available before execution.

## Methodology

The project follows an advanced **Dynamic Bayesian Synthetic Control (DBSC)** approach:

- **Traditional SCM Limitations:** Static nature struggles with high-dimensional data and time-dependent factors.
- **DBSC Enhancement:** Uses Bayesian priors and probabilistic inference to model evolving relationships dynamically.
- **Inference Techniques:** Kalman Filtering and Markov Chain Monte Carlo (MCMC) methods improve estimation accuracy.
- **Financial Applications:** Evaluates causal impacts on factor portfolios, considering external market conditions.

## Empirical Results

- **Time-Varying Treatment Effects:** The model dynamically adjusts treatment estimates based on financial market shifts.
- **Comparison with Traditional SCM:** Demonstrates improved accuracy in estimating economic interventions.
- **Macroeconomic Influence:** Assesses external economic factors such as interest rates and inflation.

## Implementation Details

- **Supporting Materials:** [RiskLab](http://risklab.ca/deep-pde)
- **Reproducible Notebooks:** [RiskLabAI Notebooks](http://github.com/RiskLabAI/Notebooks.py/tree/main/pde)

## Author

**Aviel Avshalumov, Hamid Arian, Luis Seco**

## License

This project is licensed under the MIT License.

