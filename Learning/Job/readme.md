# Work Type (Intern or not) Prediction

This project is part of a machine learning exploration where we aim to predict whether a person is an Intern or not, based on various features.

## 🧠 Problem Statement

We are classifying individuals based on their `Work Type` — predicting whether the Type is **Intern** or **not**.

## ⚙️ Data Preprocessing

- **Handling Missing Values**:

  - **Categorical Features**: Imputed using **mode**.
  - **Numerical Features**: Imputed using **mean**.

- **Target Transformation**:
  - The `Work Type` feature is converted to binary:
    - `1` if Work Type == 'Intern'
    - `0` otherwise

## 🔍 Algorithms Used

We implemented and compared the performance of the following classification algorithms:

- **K-Nearest Neighbors (KNN)**
- **SVM**
- **Logistic Regression**

## 📊 Results

- **SVM**: **80%**
- **KNN Accuracy**: **75%**
- **Logistic Regression**: **70%**

### ✅ Conclusion:

The **এশ** model performed better than the KNN model for this classification task, achieving higher prediction accuracy.
