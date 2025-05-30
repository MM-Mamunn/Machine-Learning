# Experience Years Prediction

This project is part of a machine learning exploration where we aim to predict whether a person has more than 10 years of experience or not, based on various features.

## 🧠 Problem Statement

We are classifying individuals based on their `Experience_Years` — predicting whether the experience is **over 10 years (1)** or **10 years or less (0)**.

## ⚙️ Data Preprocessing

- **Handling Missing Values**:

  - **Categorical Features**: Imputed using **mode**.
  - **Numerical Features**: Imputed using **mean**.

- **Target Transformation**:
  - The `experience_years` feature is converted to binary:
    - `1` if experience > 10 years
    - `0` otherwise

## 🔍 Algorithms Used

We implemented and compared the performance of the following classification algorithms:

- **K-Nearest Neighbors (KNN)**
- **Neural Network (NN)**
- **SVM**
- **Naive Bayes**

## 📊 Results

- **Neural Network Accuracy**: **89%**
- **SVM Accuracy**: **88%**
- **Naive Bayes Accuracy**: **88%**
- **KNN Accuracy**: **85%**

### ✅ Conclusion:

The **Neural Network** model performed better than the KNN model for this classification task, achieving higher prediction accuracy.
