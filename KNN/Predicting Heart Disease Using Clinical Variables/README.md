# K-Nearest Neighbors (KNN) Classification Model

This repository contains a basic implementation of the K-Nearest Neighbors (KNN) algorithm using Python and `scikit-learn`.

---

## 📂 Dataset

Dataset used: [Kaggle Dataset Link](https://www.kaggle.com/datasets/thedevastator/predicting-heart-disease-risk-using-clinical-var/data)  

---

## 🧠 Overview

This demonstrates a straightforward implementation of a KNN model without any complex preprocessing or feature engineering. Below are the key points:

### ✅ 1. Basic KNN Model
- Implemented using `scikit-learn`
- Used `train_test_split` and `StandardScaler` to prepare the data
- Trained using `KNeighborsClassifier`

### ❌ 2. No Data Analysis or Preprocessing
- No EDA (Exploratory Data Analysis)
- No feature selection or transformation beyond basic scaling

### 📉 3. Elbow Method for Optimal `k`
- Evaluated model accuracy for different values of `k` (number of neighbors)
- Plotted an **Elbow Chart** to visualize accuracy vs. `k`

### 🔍 4. Accuracy Evaluation
- Highest test accuracy observed at **k = 26**
- Also checked training accuracy at `k = 26`
- No significant gap between training and test accuracy, so model **does not appear to be overfitting**

---

##
