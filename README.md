# Linear Regression Practice Projects

## 📄Project Overview

This repository contains 5 practice projects for learning and applying Linear Regression using

Python.

Each dataset demonstrates simple or multiple linear regression, including model fitting, 

evaluation, and predictions.

## 🗂️ Datasets

### Study Hours → Exam Score

File: study_hours.csv

Goal: Predict exam scores based on study hours.

### House Size → Price

File: house_size_price.csv

Goal: Predict house price from its size (in m²).

### Salary → Experience

File: salary_experience.csv

Goal: Predict salary (in k) based on years of experience.

### House Price → Size (Single Feature)

File: house_size_price.csv

Goal: Predict house price from size (in m²).

### Advertising Spend → Sales

File: advertising_sales.csv

Goal: Predict sales (in k) based on spend on TV, radio, and social media advertising.

## 🧮 Tasks

For each dataset:

### Fit Linear Regression Model

Simple LR: single feature → target

Multiple LR: multiple features → target

### Report Model Parameters

Slope(s)/Coefficient(s)

Intercept

### Evaluate Model

Compute R² score to see how well the model fits.

### Make Predictions

Predict target for new input values.

## 🛠️ Python Libraries Used

pandas → Data loading & manipulation

scikit-learn → Linear regression modeling

sklearn.metrics → Model evaluation (R² score)

## Future Scope

The projects in this repository provide a strong foundation in Linear Regression, but there are many ways to extend and improve these models:

### Feature Expansion

Include additional relevant features for better prediction accuracy.

Example: For house prices, add location, year_built, floor, etc.

For sales prediction, include seasonality, discounts, or online_ads.

### Multiple & Polynomial Regression

Move beyond simple linear regression to multiple regression or polynomial regression to capture more complex relationships between variables.

Regularization Techniques

Apply Ridge, Lasso, or ElasticNet regression to reduce overfitting and improve generalization.

### Model Evaluation & Validation

Use train-test split or cross-validation for robust evaluation.

Analyze residuals to check assumptions of linear regression.

### Predictive Analytics Applications

Extend these models to real-world applications such as:

Predicting employee salaries for HR planning

Forecasting sales for marketing strategy

Estimating property values in real estate

Student performance prediction and personalized learning

### Visualization & Interpretability

Use scatter plots, regression lines, and residual plots to better interpret model performance.

Explore feature importance for multiple regression models.

### Integration with Machine Learning Pipelines

Combine with automated pipelines using scikit-learn’s Pipeline or ColumnTransformer for preprocessing and modeling.
