# Drug Classification Project Readme

## Introduction

Hello! In this repository you will find a project related to drug classification based on patient attributes. In this readme, I will provide an overview of the project, details about the dataset, the steps taken in data processing, the various models employed, and the conclusive findings.

## Project Overview

### Dataset
The dataset consists of information related to drug prescriptions and includes the following columns:

- Age
- Sex
- BP (Blood Pressure)
- Cholesterol
- Na_to_K (Sodium-to-Potassium Ratio)
- Drug

### Objective
The primary goal of this project is to classify drugs based on patient attributes. I performed data cleaning, preprocessing, and utilized several classification models to achieve accurate predictions.

## Project Steps

1. Exploratory Data Analysis (EDA)
2. Data Preprocessing
3. Modeling
4. Evaluation
## Model Evaluation

Evaluated each model using the following metrics:

- **Accuracy Score**
- **Classification Report:** Precision, Recall, F1-Score.

## Conclusion

After thorough evaluation, the models achieved the following accuracy rates:

- **98% Accuracy:**
  - Decision Tree Classifier
  - LightGBM
  - XGBoost
  - Gradient Boosting
  - Bagging Classifier

- **95% Accuracy:**
  - Logistic Regression
  - Random Forest

- **88% Accuracy:**
  - K-Neighborhood Classifier

Upon reviewing the classification report, the selected model for minimizing errors and consequences was XGBoost. It had a small error in recommending DrugX when it should have recommended DrugC, which seemed to have fewer repercussions.

## Running the Project

To run this project on your own, follow these steps:
1. Load the dataset from the provided link.
2. Execute each cell in the notebook sequentially.
3. Make sure to install any required packages if prompted.
4. Review the results and explore visualizations in the notebook.

## Python Packages Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- lightgbm
- xgboost

Ensure you have these packages installed before running the notebook. You can install them using this command:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm xgboost
