# 💊 Drug Type Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting the appropriate **drug type** for a patient based on medical attributes such as age, sex, blood pressure, cholesterol level, and sodium-to-potassium ratio.

It is a beginner-friendly machine learning project that demonstrates the complete pipeline from **data preprocessing → visualization → model training → evaluation**.

---

## 🎯 Objective

To build a classification model that can accurately predict the type of drug a patient should be prescribed.

---

## 📂 Dataset Features

| Feature     | Description                         |
| ----------- | ----------------------------------- |
| Age         | Age of the patient                  |
| Sex         | Gender (M/F)                        |
| BP          | Blood Pressure (LOW/NORMAL/HIGH)    |
| Cholesterol | Cholesterol Level (LOW/NORMAL/HIGH) |
| Na_to_K     | Sodium to Potassium ratio           |
| Drug        | Target variable (drug type)         |

---

## ⚙️ Technologies Used

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔄 Workflow

1. Data Loading
2. Data Preprocessing

   * Label Encoding for categorical variables
   * Manual mapping for ordinal features (BP, Cholesterol)
3. Data Visualization
4. Train-Test Split
5. Model Training

   * Decision Tree
   * KNN
   * Logistic Regression
6. Model Evaluation

   * Accuracy Score
   * Confusion Matrix
   * Classification Report

---

## 📊 Visualizations

* Drug Distribution
* Feature vs Target plots (Sex, BP, Cholesterol)
* Boxplots for numerical features
* Correlation Heatmap
* Confusion Matrix

---

## 🤖 Model Performance

The model is evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision, Recall, F1-score





## 📌 Key Learnings

* Handling categorical data in ML
* Difference between Label Encoding and Manual Mapping
* Importance of data visualization
* Model evaluation techniques
* Building end-to-end ML pipeline

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Use of advanced models (Random Forest, XGBoost)
* Deploying model using Flask/Streamlit

---

## 👨‍💻 Author

Tejas Mishra

---

