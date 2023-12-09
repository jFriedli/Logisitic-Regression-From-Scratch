# Jupyter Notebook Analysis: "Spaceship Titanic Dataset Exploration"
#### Mirror from Kaggle: [Space Titanic Logistic Regression from Scratch](https://www.kaggle.com/code/jbfriedli/space-titanic-logistic-regression-from-scratch)
#### Focus: Logistic Regression from Scratch

## Overview

This Jupyter Notebook provides a detailed exploration of the Spaceship Titanic dataset. It covers data loading, cleaning, exploration, pre-processing, modeling, and submission for a machine learning task. 

### 🖖 Import Section
- Libraries: `copy, math, numpy, pandas, os, matplotlib, seaborn, wordcloud, category_encoders, sklearn, scipy`.
- Purposes: Data manipulation, visualization, pre-processing, and model evaluation.

### 🛰️ Load Data
- Data Source: Kaggle's Spaceship Titanic dataset.
- Files: `sample_submission.csv`, `train.csv`, `test.csv`.
- Dataframes: `df_train` and `df_test`.

### 🚀 Data Exploration & Cleaning
- Data Information: `df_train.info()` and `df_train.head()`.
- Numerical Analysis: Descriptive statistics.
- Takeaways: Inferences about data range, spending habits, and potential feature engineering.

### 📝 Key Observations
- Handling of categorical and numerical features.
- Feature Engineering: Total billed, groups, and family relations.
- Unique insights from passenger data.

### 🔭 Data Visualization
- Correlation matrix and various plots.
- Analysis of features like Age, Total Billed, Related People, Groups.
- Categorical Data Analysis: HomePlanet, CryoSleep, VIP, Cabin Deck, Cabin Side.

### 🛸 Pre Processing
- Data Preprocessing: Dropping irrelevant columns, imputation, scaling.
- One-hot encoding for categorical data.

### 🤖 Model: Logistic Regression
- Model Details: Logistic Regression with regularization.
- Iterative Training: Adjusting learning rate and cut-off.
- Evaluation: Accuracy and Confusion Matrix.

### 🌠 Submission
- Preparing the submission file.
