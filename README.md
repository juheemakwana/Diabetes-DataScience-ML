# Diabetes-DataScience-ML
This repository focuses on diabetes prediction using health indicator datasets. It includes data preprocessing, EDA, feature selection, handling imbalanced data, and building ML models like Logistic Regression, Decision Trees, KNN, and Random Forest, with techniques like SMOTE and ANOVA for feature optimization and predictive accuracy.

## Datasets
- **2015 Behavioral Risk Factor Dataset**: [Source - Kaggle](https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system?select=2015.csv)
  - File: `data/2015.csv`
  - Description: Contains behavioral risk factor data from the 2015 CDC survey.

## Added Python code for Part I: Data Cleaning and Binary Classification
- Included data preprocessing steps to clean and prepare the dataset.
- Implemented binary classification logic for the target variable.
- Generated a cleaned and preprocessed dataset ready for use in ML models.
- This script is a foundational step for building ML workflows in the data science project.

## Running Code from Google Colab in Jupyter Lab
I initially developed the code in Google Colab. Now, I am running the file in Jupyter Lab. To achieve this, I converted the Jupyter Notebook (.ipynb) file to a Python script using the following command in the terminal:
jupyter nbconvert --to script Python_code_part_I.ipynb

To execute the Python script, use the command below in the terminal:
python Python_code_part_I.py

## Uploaded output files from Part I: Data Cleaning and Binary Classification

- Includes cleaned and preprocessed datasets:
  - Diabetes Full dataset (BRFSS 2015 health indicators)
  - Diabetes Binary classification dataset
  - Balanced binary classification dataset (50-50 split)
- Files are ready for use in ML model development.

# Key Steps and Features:
PART-I
## Data Cleaning:

Renaming and formatting feature names for readability.

Creating binary datasets for "Diabetes" vs. "No Diabetes."

Saving processed datasets, including a 50-50 balanced binary dataset, to CSV.

PART-II
## Exploratory Data Analysis (EDA):

Identifying trends, distributions, and correlations in the data.
Feature Selection and Engineering:

Variance Inflation Factor (VIF) analysis for multicollinearity.
ANOVA for feature importance and selection.
Identifying the best features for predictive modeling.
