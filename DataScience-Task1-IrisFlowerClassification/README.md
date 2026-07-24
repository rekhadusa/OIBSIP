# 🌸 Iris Flower Classification

## 📌 Project Overview
This project aims to classify Iris flowers into three different species—**Setosa**, **Versicolor**, and **Virginica**—using Machine Learning algorithms. The classification is based on four flower measurements: Sepal Length, Sepal Width, Petal Length, and Petal Width.

---

## 🎯 Objective
To build and evaluate Machine Learning models that can accurately predict the species of an Iris flower based on its physical features.

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
The Iris dataset was loaded directly from **scikit-learn** using `load_iris()`. No external dataset was required.

---

## 📊 Project Workflow
- Loaded the Iris dataset
- Performed Exploratory Data Analysis (EDA)
- Checked dataset shape, data types, null values, and summary statistics
- Created Pairplot and Boxplots for visualization
- Selected the most important features
- Split the dataset into Training (80%) and Testing (20%)
- Trained two Machine Learning models:
  - Logistic Regression
  - K-Nearest Neighbours (KNN)
- Evaluated the models using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)

---

## 📈 Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **100%** |
| K-Nearest Neighbours (KNN) | **100%** |

---

## 🏆 Best Performing Model

Although both models achieved **100% accuracy** on the test dataset, **Logistic Regression** was selected as the best-performing model because it is simpler, faster, and provides excellent performance on the Iris dataset. It generalizes well while maintaining perfect classification accuracy.

---

## 📌 Conclusion

The Iris Flower Classification project successfully classified all three Iris species with excellent performance. Logistic Regression was selected as the final model due to its simplicity, efficiency, and perfect accuracy on the test data.

---

## 👩‍💻 Author
   **Rekha**
