# Car Price Prediction with Machine Learning

## Oasis Infobyte Data Science Internship — Task 2

### Project Overview

This project focuses on predicting the selling price of used cars using machine learning regression techniques.

The project follows a complete machine learning workflow, including data cleaning, feature engineering, exploratory data analysis, data preprocessing, model training, model evaluation, model comparison, and feature importance analysis.

## Objective

The objective of this project is to build machine learning regression models that predict the selling price of used cars based on their features.

## Dataset

The dataset contains 8,128 records and 12 original features.

### Features

- `name` — Name of the car
- `year` — Manufacturing year
- `selling_price` — Selling price of the car
- `km_driven` — Kilometers driven
- `fuel` — Fuel type
- `seller_type` — Type of seller
- `transmission` — Transmission type
- `owner` — Ownership information
- `mileage(km/ltr/kg)` — Mileage
- `engine` — Engine capacity
- `max_power` — Maximum engine power
- `seats` — Number of seats

## Data Cleaning

The following preprocessing steps were performed:

- Checked for missing values
- Converted numerical columns into appropriate numeric formats
- Handled missing numerical values using median imputation
- Identified and removed duplicate records
- Checked categorical features
- Prepared the dataset for machine learning

After removing duplicate records, the dataset contained 6,926 records.

## Feature Engineering

### Car Age

Car age was calculated from the manufacturing year.

`Car Age = 2026 - Manufacturing Year`

### Brand Extraction

The car brand was extracted from the car name.

Example:

`Maruti Swift Dzire → Maruti`

## Exploratory Data Analysis

The following visualizations were performed:

- Distribution of selling prices
- Selling price vs. fuel type
- Selling price vs. car age
- Feature correlation heatmap

These visualizations were used to understand the dataset and identify relationships between different features and selling price.

## Data Preprocessing

Categorical features were converted into numerical representations using One-Hot Encoding.

Categorical features include:

- Fuel
- Seller Type
- Transmission
- Owner
- Brand

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

A `random_state` of 42 was used for reproducibility.

## Machine Learning Models

Two regression models were trained:

### 1. Linear Regression

Linear Regression was used as a baseline regression model.

### 2. Random Forest Regressor

Random Forest Regressor was used to capture complex relationships between car features and selling price.

## Model Evaluation

The models were evaluated using:

- **MAE (Mean Absolute Error)** — Lower is better
- **RMSE (Root Mean Squared Error)** — Lower is better
- **R² Score** — Higher is better

## Model Comparison

The performance of Linear Regression and Random Forest Regressor was compared using MAE, RMSE, and R² Score.

Based on the evaluation results, the **Random Forest Regressor** was selected as the best-performing model.

## Feature Importance

Feature importance analysis was performed using the Random Forest Regressor.

A Top 10 Feature Importance chart was created to identify the most influential features for predicting car selling prices.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Missing Value Handling
   ↓
Duplicate Removal
   ↓
Feature Engineering
   ↓
Exploratory Data Analysis
   ↓
Correlation Analysis
   ↓
Categorical Encoding
   ↓
Train-Test Split
   ↓
Linear Regression
   ↓
Random Forest Regressor
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Feature Importance
   ↓
Final Model Selection
