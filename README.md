# Do Higher Wages Lead to Better Performance in the Premier League?

## Table of contents
* [Introduction](#Introduction)
* [Technologies](#Technologies)
* [Data](#Data)
* [Methods](#Methods)
* [Key Findings](#Key-Findings)

## Introduction
This project investigates whether higher wage expenditure leads to improved performance in the Premier League. By using regression analysis, the project explores the relationship between annual team wages and points scored, while testing alternative specifications and the model's robustness.

## Technologies 
The project is created using:
* Python 3.12.7 (Jupyter Notebook)

## Data
The analysis uses:
- Premier League Standings Data (points, wins, goals, etc.)
- Team Salary Data

All datasets are stored within the `Source Code` ZIP folder found in the Git repository.

## Methods 
The following models are used:

- Baseline OLS regression (log wages vs points scored)
- Controlled regression (including squad size)
- Nonlinear (quadratic) wage model
- Residual analysis to identify overperforming and underperforming teams

Additional models, such as interaction effects and wage per player, are included to test the robustness of the analysis.

## Key Findings
- Higher wages are typically associated with higher points scored
- Squad size has little explanatory power for points scored
- Limited evidence of diminishing returns to spending
- Some teams significantly outperform their wage bill and vice versa
