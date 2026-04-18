# Markowitz Portfolio Optimization & Stability Analysis

This project implements and analyzes portfolio optimization using the Markowitz mean-variance framework.

## Overview

The notebook explores:

- Efficient frontier construction
- Maximum Sharpe ratio portfolio
- Capital Market Line (CML)
- Impact of short selling
- Sensitivity to estimation error
- Instability of optimal portfolios
- Stabilization techniques (shrinkage & regularization)

## Key Results

- The maximum-Sharpe portfolio is highly sensitive to estimation errors.
- Small perturbations in expected returns lead to large changes in allocations.
- Regularization and shrinkage significantly improve stability.

## Methods

- Mean-variance optimization
- Numerical optimization (SciPy)
- Monte Carlo simulations
- Visualization of portfolio distributions

## Structure

- `markowitz_analysis.ipynb`: main notebook with all analysis

## Requirements

Install dependencies with:

```bash
pip install -r requirements.txt