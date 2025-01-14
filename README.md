# Diabetes-DataScience-ML
This repository focuses on diabetes prediction using health indicator datasets. It includes data preprocessing, EDA, feature selection, handling imbalanced data, and building ML models like Logistic Regression, Decision Trees, KNN, and Random Forest, with techniques like SMOTE and ANOVA for feature optimization.

## Datasets
- **2015 Behavioral Risk Factor Dataset**: [Source - Kaggle](https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system?select=2015.csv)
  - File: `data/2015.csv`
  - Description: Contains behavioral risk factor data from the 2015 CDC survey.

## Added Python code for Part I: Data Cleaning and Binary Classification
- Included data preprocessing steps to clean and prepare the dataset.
- Implemented binary classification logic for the target variable.
- Generated a cleaned and preprocessed dataset ready for use in ML models.
- This script is a foundational step for building ML workflows in the data science project.

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

## Data Splitting and Imbalance Handling:

Splitting data into training and testing sets.
Addressing class imbalance using techniques like SMOTE and NearMiss.

## Data Scaling:

Standardizing features for consistent model performance.
Modeling and Evaluation:

Implementation of various machine learning models, including:
Logistic Regression
Decision Tree
K-Nearest Neighbors (KNN)
Random Forest
Evaluation using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

