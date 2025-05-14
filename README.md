# final-project-stsci6020-2025
Final Project for BTRY6020
Wine Quality Prediction: Linear Regression Analysis
Project Overview
This repository contains a statistical analysis of the Wine Quality dataset from the UCI Machine Learning Repository. The project explores how chemical properties of red wine influence quality ratings, using linear regression techniques to develop predictive models that could assist winemakers in production decisions.
Dataset
The dataset contains 1,599 red wine samples from Portuguese "Vinho Verde" wines, with:

11 physicochemical properties (input variables)
Quality ratings on a scale of 0-10 (output variable)

Files Description

Final_Project_Analysis.Rmd: R Markdown file containing all code and analysis
Final_Project_Analysis.html: Rendered HTML report of the analysis
README.md: This file with project description

How to Run the Analysis

Clone this repository
Ensure you have R and RStudio installed
Install the required packages:
Rinstall.packages(c("car", "lmtest", "sandwich", "MASS", "lmboot"))

Open the R Markdown file in RStudio
Run the entire document using the "Knit" button

Required Packages

car: For VIF analysis
lmtest: For Breusch-Pagan test
sandwich: For robust standard errors
MASS: For stepwise selection
lmboot: For bootstrap confidence intervals

Key Findings

Alcohol content, volatile acidity, and sulphates are the most influential predictors of wine quality
The effect of alcohol on quality is stronger when volatile acidity is lower (significant interaction)
The final model explains approximately 44% of the variance in wine quality
Practical recommendations for winemakers include increasing alcohol content and sulphates while reducing volatile acidity

Limitations

Dataset includes only wines from a specific Portuguese region
Some regression assumptions are violated
Independence of observations cannot be fully verified
