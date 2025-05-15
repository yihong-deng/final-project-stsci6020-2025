# final-project-stsci6020-2025
Final Project for BTRY6020
Wine Quality Prediction: Linear Regression Analysis
##Project Overview
This repository contains a statistical analysis of the Wine Quality dataset from the UCI Machine Learning Repository. The project explores how chemical properties of red wine influence quality ratings, using linear regression techniques to develop predictive models that could assist winemakers in production decisions.
Dataset
The dataset contains 1,599 red wine samples from Portuguese "Vinho Verde" wines, with:

11 physicochemical properties (input variables)
Quality ratings on a scale of 0-10 (output variable)

##Files Description

Final_Project.Rmd: R Markdown file containing all code and analysis
Final_Project.html: Rendered HTML report of the analysis
README.md: This file with project description

##Data Source

The dataset used in this analysis is from:
- UCI Machine Learning. "Red Wine Quality." Kaggle, 2018. https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009

The raw data is loaded directly from a Google Drive link in the R Markdown file.

## How to Run the Analysis

### Prerequisites

Ensure you have R and RStudio installed. The analysis requires the following packages:
- lmtest
- sandwich
- lmboot

### Running the Analysis

1. Clone this repository to your local machine
2. Open the `Final_Project.Rmd` file in RStudio
3. Install required packages if not already installed using:
   ```r
   install.packages(c("lmtest", "sandwich", "lmboot"))
   ```
4. Click "Knit" in RStudio to generate the PDF report, or run individual code chunks to explore specific parts of the analysis

### Note on Data Access

The dataset is accessed via a Google Drive link in the code. If you encounter issues accessing the data, you can download the dataset from Kaggle (link above) and modify the file path in the data loading section accordingly.
