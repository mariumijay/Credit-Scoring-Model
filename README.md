# Credit-Scoring-Model

# 🧠 Creditworthiness Prediction using ML
A machine learning project that predicts an individual's creditworthiness using financial data and classification algorithms like Random Forest, Logistic Regression, and Decision Tree. Includes model evaluation, preprocessing, and user-interactive predictions.This project uses Machine Learning models to **predict whether a person is creditworthy** based on their past financial history, using the `bank.csv` dataset.

## 📌 Objective
To build a classification model that predicts **creditworthiness** (yes/no) using features like age, job, balance, and more.

## 🛠️ Technologies Used
- Python
- Pandas, NumPy, Matplotlib
- Scikit-learn (Random Forest, Logistic Regression, Decision Tree)
- VS Code + GitHub Codespaces

## 📂 Dataset
- Dataset used: `bank.csv`
- Features include:
  - Age, job, marital status, education
  - Default, balance, housing, loan
  - Contact, duration, campaign, previous
  - Target: `y` (yes/no — creditworthy or not)

## 🔍 Preprocessing Steps
- Removed null and duplicate values
- Label encoding for categorical columns
- Feature-target splitting
- 80-20 train-test split

## 🤖 Models Applied
- ✅ Random Forest Classifier
- ✅ Logistic Regression
- ✅ Decision Tree Classifier

## 🧪 Evaluation Metrics
- Accuracy, Precision, Recall, F1-score
- ROC-AUC Score
- Log Loss
- Confusion Matrix

## 📊 Sample Output

```plaintext
Classification report: 
              precision    recall  f1-score   support
           0       0.92      0.98      0.95       807
           1       0.60      0.27      0.37        98
Accuracy: 0.90
ROC AUC: 0.91
