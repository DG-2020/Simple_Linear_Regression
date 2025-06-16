

## ***Simple Linear Regression with the Palmer Penguins Dataset***
This repository contains a Jupyter Notebook that provides a step-by-step walkthrough of building and evaluating a simple linear regression model. The project uses the well-known Palmer Penguins dataset to predict a penguin's body mass based on its bill length, serving as a classic example of regression analysis.

📋 **Project Overview**
The primary goal of this analysis is to determine if a linear relationship exists between the bill length and body mass of penguins. The notebook covers the entire workflow from data loading and cleaning to model fitting and residual analysis.

The key questions addressed are:

-> *Is bill length a significant predictor of body mass?*

->*What is the nature of the relationship (positive/negative, strong/weak)?*

->*How well does the linear model fit the data?*

🐧 **Dataset**
The analysis uses the Palmer Penguins dataset, which is conveniently available through the seaborn library. This dataset was collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER.

It contains size measurements for three penguin species (Adelie, Chinstrap, and Gentoo) observed on three islands in the Palmer Archipelago, Antarctica.

⚙️ **Analysis Workflow**
The Jupyter Notebook is structured into the following key steps:

Environment Setup: Imports the necessary Python libraries for data manipulation, visualisation, and modelling (pandas, seaborn, matplotlib, statsmodels).

Data Loading and Cleaning: Loads the penguins dataset and handles missing values to prepare a clean dataset for modelling.

Exploratory Data Analysis (EDA): A regression plot (seaborn.regplot) is created to visually inspect the relationship between bill_length_mm and body_mass_g.

Model Fitting: An Ordinary Least Squares (OLS) model is fitted using the statsmodels library.

Model Evaluation: The model.summary() function is used to generate a detailed table of statistical results, including:

-> R-squared (R^2)

-> Coefficients for the intercept and slope

-> Standard errors, t-statistics, and p-values

-> Residual Analysis: To validate the model's assumptions, a Residuals vs. Fitted Values plot is generated. This plot helps in checking for non-linear patterns, heteroscedasticity, and outliers.

📊 **Key Visualisations**
The notebook produces two primary visualisations to interpret the data and model results:

-> Regression Plot: Shows the data points and the fitted regression line, illustrating the linear relationship.

-> Residual Plot: Plots the model residuals against the fitted values to diagnose model fit.
