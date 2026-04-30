# Do Higher Wages Lead to Better Performance in the Premier League?

![This is a image](Premier_League_Logo.png)

## Table of contents 📚

* [Introduction 📝](#Introduction)
* [Technologies 💻](#Technologies)
* [Data 📊](#Data)
* [Methods 🛠️](#Methods)
* [Key Findings 💡](#Key-Findings) 
* [Project Replication Instructions 📌](#Project-Replication-Instructions)


## Introduction 📝

This project investigates whether higher wage expenditure leads to improved performance in the Premier League. By using regression analysis, the project explores the relationship between annual team wages and points scored, while testing alternative specifications and the model's robustness.

In professional football leagues, particularly the Premier League, it is assumed that big teams possessing greater financial power typically achieve better performances. However, it is not always clear how strong or consistent this relationship is. Therefore, this project aims to evaluate whether wage expenditure truly explains the differences in team performance and whether alternative measures, such as squad size or wage distribution, offer additional explanatory power.

The project was driven by personal interest towards the Premier League as my most-watched football league, as well as its availability of data, which allows for an insightful exploration towards how economic factors translate into sporting success.  


## Technologies 💻

The project is created using:
* Python 3.12.7 (Jupyter Notebook)


## Data 📊

The analysis uses:
- Premier League Standings Data (points, wins, goals, etc.)
- Team Salary Data (annual salary, squad size)

All datasets are stored within the 'Source Code.zip' folder found in the Git repository.


## Methods 🛠️

The following models are used:

- Baseline OLS regression (log wages vs points scored)
- Controlled regression (including squad size)
- Nonlinear (quadratic) wage model
- Residual analysis to identify overperforming and underperforming teams

Additional models, such as interaction effects and wage per player, are included to test the robustness of the analysis.


## Key Findings 💡

- Higher wages are typically associated with higher points scored
- Squad size has little explanatory power for points scored
- Limited evidence of diminishing returns to spending
- Some teams significantly outperform their wage bill and vice versa


## Project Replication Instructions 📌

1. Clone this repository
2. Unzip 'Source Code' from the Git repository
3. Download 'standings.csv' and 'team_salary.csv' into a Jupyter Notebook folder
4. Open 'Main Code.ipynb' in Jupyter Notebook in the same folder
5. Run all cells

Required libraries:
- pandas
- numpy
- matplotlib
- statsmodels
- seaborn

