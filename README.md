# Portfolio-Optimization-and-CAPM-Analysis

This repository contains the analysis and implementation of two cornerstone financial theories: Markowitz's Portfolio Theory for efficient frontier construction and the Capital Asset Pricing Model (CAPM) for evaluating expected returns on assets given their risk profiles.

## Project Overview

### Markowitz Portfolio Theory

- **Objective**: Apply Markowitz's mean-variance optimization to construct the efficient frontier from a selection of 10 market assets.
- **Methods**:
  - Data collection on closing prices over the last 3 months for chosen assets.
  - Calculation of simple/log returns.
  - Construction of the efficient frontier and identification of optimal portfolios for different risk levels.

### Capital Asset Pricing Model (CAPM)

- **Objective**: Utilize the CAPM formula to determine the expected returns for the same 10 risky assets and analyze the Capital Market Line (CML).
- **Methods**:
  - Selection of a risk-free asset and calculation of its yield.
  - CAPM-based expected return calculation for each risky asset.
  - Construction and analysis of the CML, identification of the tangency point on the efficient frontier, and calculation of performance measures for portfolio evaluation.

## Contents

- **Data/**: Contains the datasets used for analysis.
- **Analysis/**: 
  - `Portfolio_Optimization.ipynb`: Jupyter notebook with Markowitz portfolio theory analysis.
  - `CAPM_Analysis.ipynb`: Jupyter notebook with CAPM analysis and CML construction.
- **Presentation/**: PowerPoint presentation summarizing key findings and methodologies.
- **README.md**: This file, providing an overview of the project and repository structure.

## Key Findings

- **Efficient Frontier**: Our analysis presents the efficient frontier for the chosen assets, indicating the trade-off between risk and return.
- **Optimal Portfolios**: Weights for optimal portfolios at two selected risk levels on the efficient frontier are provided.
- **CAPM and CML**: The expected returns calculated using CAPM, along with the CML plot, offer insights into the risk-return profile of our assets versus the market.
- **Performance Measures**: Analysis of Sharpe and Treynor ratios highlights the performance and risk-adjusted returns of our optimized portfolios.

## Discussion

- Our findings elucidate the critical balance between risk and return in portfolio selection, underscoring the practical utility of Markowitz optimization and CAPM in real-world investment strategies.
- Limitations of these models, including the assumption of a static investment universe and the reliance on historical data for future performance prediction, are also discussed.

## Usage

Feel free to clone this repository for further analysis or as a basis for your investment strategy exploration. Ensure you have Python installed, along with necessary libraries like `pandas`, `numpy`, `matplotlib`, and `scipy` for optimization tasks.

