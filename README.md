# Pokemon Regression and Classification Analysis

This repository contains code for conducting regression and classification analysis on Pokemon data. The analysis involves exploring the relationship between various attributes of Pokemon and predicting whether a Pokemon is legendary or not.

## Regression Analysis

### Description

The regression analysis focuses on two attributes of Pokemon: Special Attack (Sp_Atk) and Special Defense (Sp_Def). The goal is to understand the relationship between these attributes and determine if one can be predicted from the other.

### Steps

1. Imported libraries and data.
2. Selected relevant columns for analysis.
3. Conducted regression analysis using Ordinary Least Squares (OLS) method.
4. Analyzed the regression results, focusing on coefficients and p-values.
5. Visualized the regression line on a scatter plot.

## Classification Analysis

### Description

The classification analysis aims to predict whether a Pokemon is legendary or not based on its attributes. This involves preprocessing the data, handling missing values, encoding categorical variables, and training a classification model.

### Steps

1. Imported libraries and data.
2. Preprocessed the data by handling missing values and encoding categorical variables.
3. Created a new column for the target variable (isLegendary).
4. Split the data into training and testing sets.
5. Created a Random Forest Classifier model.
6. Evaluated the accuracy of the model on both the training and testing sets.

## Usage

To run the regression and classification analysis:

1. Clone the repository to your local machine.
2. Ensure you have Python installed along with the required libraries (pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn).
3. Open the Jupyter Notebook file (`Pokemon_Analysis.ipynb`) in a Jupyter Notebook environment.
4. Execute the cells in the notebook to perform the analysis step by step.

## Data Source

The dataset used for this analysis is `pokemon.csv`.

## Dependencies

Ensure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scikit-learn

You can install these libraries via pip using the following command:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
