# Car Price Prediction with Machine Learning

## 📌 Project Overview

This project aims to predict the selling price of used cars using Machine Learning regression algorithms. The prediction is based on various vehicle features such as manufacturing year, kilometers driven, fuel type, transmission, mileage, engine capacity, maximum power, seats, car age, and brand.

---

## 🎯 Objective

To build and evaluate Machine Learning regression models that can accurately predict the selling price of a used car based on its features.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains information about used cars, including their name, manufacturing year, selling price, kilometers driven, fuel type, seller type, transmission, ownership, mileage, engine, maximum power, and number of seats.

The original dataset contains **8,128 records and 12 features**.

After handling missing values and removing **1,202 duplicate records**, the final dataset contains **6,926 records**.

---

## 📊 Project Workflow

- Loaded the used car dataset
- Performed data cleaning and preprocessing
- Checked missing values and handled numerical missing values using median imputation
- Identified and removed duplicate records
- Performed Exploratory Data Analysis (EDA)
- Analyzed selling price distribution
- Created Selling Price vs. Fuel Type boxplot
- Created Selling Price vs. Car Age scatter plot
- Created a feature correlation heatmap
- Performed feature engineering:
  - Calculated Car Age from the manufacturing year
  - Extracted Brand from the car name
- Encoded categorical features using One-Hot Encoding
- Split the dataset into Training (80%) and Testing (20%)
- Trained two Machine Learning regression models:
  - Linear Regression
  - Random Forest Regressor
- Evaluated the models using:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Compared the performance of both models
- Performed feature importance analysis using the best-performing model

---

## 📈 Results

| **Model** | **MAE** | **RMSE** | **R² Score** |
|-----------|---------|----------|--------------|
| Linear Regression | **See Notebook Output** | **See Notebook Output** | **See Notebook Output** |
| Random Forest Regressor | **See Notebook Output** | **See Notebook Output** | **See Notebook Output** |

---

## 🏆 Best Performing Model

Based on the evaluation results, **Random Forest Regressor** was selected as the best-performing model.

It achieved better overall performance compared with Linear Regression based on the MAE, RMSE, and R² Score evaluation metrics.

Random Forest was selected because it can capture complex relationships between different vehicle features and selling price while providing feature importance information.

---

## 📌 Conclusion

The Car Price Prediction project successfully developed Machine Learning regression models to predict the selling prices of used cars.

Both Linear Regression and Random Forest Regressor were trained and evaluated. Based on the evaluation results, **Random Forest Regressor** was selected as the final model.

Feature importance analysis was also performed to identify the most influential features contributing to car price prediction.

This project demonstrates practical knowledge of data preprocessing, feature engineering, exploratory data analysis, regression modelling, model evaluation, and feature importance analysis.

---

## 👩‍💻 Author

**Dusa Rekha**
