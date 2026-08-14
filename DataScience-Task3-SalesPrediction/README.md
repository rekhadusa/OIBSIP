# Sales Prediction Using Python

## 📌 Project Overview

This project focuses on predicting product sales based on advertising expenditure across different media channels such as TV, Radio, and Newspaper using Machine Learning regression techniques.

This project was completed as part of the Oasis Infobyte Data Science Internship – Task 5.

## 🎯 Objective

To build and evaluate Machine Learning regression models that predict product sales based on advertising spending across different media channels.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset

The Advertising dataset contains 200 observations with the following variables:

- TV – Advertising expenditure on TV
- Radio – Advertising expenditure on Radio
- Newspaper – Advertising expenditure on Newspaper
- Sales – Product sales

## 📊 Project Workflow

- Loaded the Advertising dataset
- Checked dataset structure and data types
- Checked missing values
- Checked and removed duplicate records
- Performed Exploratory Data Analysis (EDA)
- Created pairplots
- Created Sales vs TV scatter plot
- Created Sales vs Radio scatter plot
- Created Sales vs Newspaper scatter plot
- Created correlation matrix heatmap
- Split the dataset into training and testing sets
- Trained Linear Regression as the baseline model
- Trained Random Forest Regressor as an additional model
- Evaluated both models using MAE, RMSE, and R² Score
- Compared model performance
- Selected the best-performing model
- Created a residual plot for the best model
- Analyzed advertising channel impact using Linear Regression coefficients

## 🤖 Machine Learning Models

### 1. Linear Regression

Linear Regression was used as the baseline model for sales prediction.

### 2. Random Forest Regressor

Random Forest Regressor was trained as an additional model to capture complex relationships between advertising expenditure and sales.

## 📈 Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

For MAE and RMSE, lower values indicate better performance, while a higher R² Score indicates better model performance.

## 🏆 Best Performing Model

**Random Forest Regressor** was identified as the best-performing model based on the evaluation results.

Therefore, Random Forest Regressor was selected as the final model for sales prediction.

## 📉 Residual Analysis

A residual plot was created for the Random Forest Regressor to analyze the distribution of prediction errors and check for systematic patterns.

## 📢 Advertising Channel Impact

TV, Radio, and Newspaper advertising channels were analyzed using Linear Regression coefficients to identify their relative impact on sales.

The channel with the highest positive coefficient was considered the advertising channel with the strongest influence on sales.

## 📌 Conclusion

The Sales Prediction project successfully demonstrated an end-to-end Machine Learning workflow, including data loading, data cleaning, exploratory data analysis, visualization, model training, evaluation, model comparison, residual analysis, and interpretation.

Two regression models were trained: Linear Regression and Random Forest Regressor. Based on the evaluation metrics, **Random Forest Regressor was selected as the best-performing model**.

The project provided practical experience in applying regression techniques to a real-world sales prediction problem.

## 👩‍💻 Author

**Dusa Rekha**

**Data Science Intern – Oasis Infobyte**
