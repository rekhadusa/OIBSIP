# OIBSIP
Oasis Infobyte Data Science Internship Projects
# OASIS INFOBYTE - DATA SCIENCE INTERNSHIP

## Internship Projects

This repository contains the Machine Learning and Data Science projects completed as part of the **Oasis Infobyte Data Science Internship**.

The projects cover both **classification and regression problems**, providing practical experience in data preprocessing, exploratory data analysis, visualization, model training, evaluation, and result interpretation.

---

## Intern Details

**Name:** Dusa Rekha  
**Track:** Data Science  
**Internship:** Oasis Infobyte

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- GitHub

---

# Projects

## 1. Iris Flower Classification

### Objective

Build a Machine Learning classification model to identify the species of an Iris flower based on its physical measurements.

The three species are:

- Setosa
- Versicolor
- Virginica

### Work Performed

- Loaded the Iris dataset using `sklearn.datasets.load_iris()`
- Performed Exploratory Data Analysis (EDA)
- Checked dataset shape, data types, null values, and statistics
- Created pairplots and boxplots
- Analyzed feature importance and discriminative features
- Split the dataset into training and testing sets
- Trained two classification models
- Evaluated the models using accuracy, confusion matrix, precision, recall, and F1-score

### Models Used

- Logistic Regression
- K-Nearest Neighbours (KNN)

### Result

Both models achieved **100% accuracy** on the test dataset.

**Logistic Regression** was selected as the final model because of its simplicity, efficiency, and excellent performance.

### Project Folder

`DataScience-Task1-IrisFlowerClassification/`

---

## 2. Car Price Prediction

### Objective

Build a Machine Learning regression model to predict the selling price of used cars based on various vehicle features.

### Work Performed

- Loaded the CarDekho vehicle dataset
- Performed data cleaning
- Handled missing values
- Removed duplicate records
- Performed feature engineering
- Created car age from the year feature
- Extracted car brand information from the name
- Performed Exploratory Data Analysis
- Created price distribution and relationship visualizations
- Encoded categorical features
- Created a correlation heatmap
- Split the dataset into training and testing sets
- Trained multiple regression models
- Evaluated the models using MAE, RMSE, and R² Score
- Identified the best-performing model

### Models Used

- Linear Regression
- Random Forest Regressor

### Result

**Random Forest Regressor** was identified as the best-performing model based on the evaluation metrics and was selected for the final car price prediction.

### Project Folder

`DataScience-Task2-CarPricePrediction/`

---

## 3. Sales Prediction Using Python

### Objective

Build a Machine Learning regression model to predict product sales based on advertising expenditure across:

- TV
- Radio
- Newspaper

### Work Performed

- Loaded the Advertising dataset
- Checked dataset structure and data types
- Performed missing value and duplicate checks
- Performed Exploratory Data Analysis
- Created pairplots
- Created Sales vs TV scatter plot
- Created Sales vs Radio scatter plot
- Created Sales vs Newspaper scatter plot
- Created a correlation matrix heatmap
- Split the dataset into training and testing sets
- Trained Linear Regression as the baseline model
- Trained Random Forest Regressor as an additional model
- Evaluated models using MAE, RMSE, and R² Score
- Compared model performance
- Created a residual plot for the best model
- Analyzed advertising channel impact using model coefficients

### Models Used

- Linear Regression
- Random Forest Regressor

### Result

**Random Forest Regressor** was identified as the best-performing model based on the evaluation results and was selected as the final model for sales prediction.

### Project Folder

`DataScience-Task5-SalesPrediction/`

---

# Skills Demonstrated

Through these projects, I gained practical experience in:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- Feature Selection
- Categorical Encoding
- Classification
- Regression
- Model Training
- Model Evaluation
- Model Comparison
- Residual Analysis
- Result Interpretation
- Jupyter Notebook Development
- GitHub Project Management

---

# Machine Learning Workflow

The projects followed an end-to-end Machine Learning workflow:

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Feature Engineering / Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Best Model Selection
   ↓
Result Interpretation
