# H2O AutoML Heart Attack Prediction

---

## Abstract

The objective of this project is to construct a predictive model to assess the likelihood of a heart attack using a heart attack analysis dataset. Key features include:

- **Age**: Age of the patient *(Numerical)*
- **Sex**: Sex of the patient *(Categorical)*
- **exang**: Exercise-induced angina *(Categorical)*
- **caa**: Number of major vessels (0-3) *(Categorical)*
- **cp**: Chest Pain type *(Categorical)*
- **trtbps**: Resting blood pressure (in mm Hg) *(Numerical)*
- **chol**: Cholesterol level in mg/dl *(Numerical)*
- **fbs**: Fasting blood sugar level *(Categorical)*
- **rest_ecg**: Resting electrocardiographic results *(Categorical)*
- **thalach**: Maximum heart rate achieved *(Numerical)*
- **Oldpeak**: ST depression induced by exercise relative to rest *(Numerical)*

The dependent variable, **output**, indicates the likelihood of a heart attack (0 = less chance, 1 = more chance).

---

## Tasks Performed

### 1. Exploratory Data Analysis (EDA)

Conducted exploratory data analysis to understand the dataset's structure and characteristics, including variable distributions, missing values, and outliers.

### 2. Data Visualization

Created various visualizations such as histograms, scatter plots, and box plots to gain insights into the data and explore relationships between variables.

### 3. Data Preprocessing

Cleaned the dataset by handling missing values and outliers, and encoded categorical variables as necessary for machine learning.

### 4. Model Building

Built machine learning models using algorithms like Gradient Boosting, Random Forest, and Linear Regression to predict heart attack likelihood.

### 5. Hyperparameter Tuning

Performed hyperparameter tuning using techniques like GridSearchCV to optimize model performance.

### 6. Model Evaluation

Evaluated model performance using metrics such as RMSE, MSE, MAE, and R-squared, and visualized results for interpretation.

### 7. Statistical Analysis

Conducted statistical analysis, including the Variance Inflation Factor (VIF), to assess multicollinearity among independent variables.

### 8. Model Interpretability

Assessed the interpretability of models and their predictions in the context of the dataset.

---

## H2O AutoML

H2O AutoML is an automated machine learning platform from H2O.ai that streamlines the model development process. It automates tasks such as algorithm selection, hyperparameter tuning, and model evaluation, offering a user-friendly interface and scalability for large datasets. Users can build machine learning models efficiently without deep technical expertise, although understanding the data and results remains crucial for effective use.

---

## Usage

### Importing Required Modules and Initializing H2O

Ensure you have the necessary modules installed and initialize H2O AutoML for model training and evaluation.

### Overview

This project provides insights into heart attack prediction using machine learning techniques and showcases the capabilities of H2O AutoML for streamlined model development.
