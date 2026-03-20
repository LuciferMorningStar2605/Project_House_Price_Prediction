# House Price Prediction

Regression project that explores housing data and fits a machine learning model to estimate house prices from structured tabular features.

## Overview
This notebook focuses on exploratory data analysis and baseline regression modeling. It loads the housing dataset, inspects summary statistics, studies feature relationships with correlation analysis, and trains a regression model after a train-test split.

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Workflow
1. Load the housing dataset from `data.csv`
2. Inspect feature distributions and descriptive statistics
3. Study correlations between variables
4. Visualize relationships with heatmaps and boxplots
5. Split the data into training and test sets
6. Train a baseline linear regression model

## Model Notes
- Problem type: regression
- Baseline model: linear regression
- Focus area: exploratory analysis and feature relationships

## Files
```text
Project_House_Price_Prediction/
├── data.csv
├── project_house.ipynb
├── Requirements.txt
└── README.md
```

## Run Locally
```bash
pip install -r Requirements.txt
jupyter notebook project_house.ipynb
```

## Learning Focus
- Exploratory analysis for tabular data
- Correlation-based feature understanding
- Building and evaluating baseline regression models
- Turning raw housing data into a modeling workflow
