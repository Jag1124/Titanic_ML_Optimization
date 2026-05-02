# 🚢 Titanic ML Optimization Project

## 📌 Overview

This project focuses on predicting passenger survival on the Titanic dataset using Machine Learning. It includes a complete pipeline covering data preprocessing, feature engineering, model building, hyperparameter tuning, and performance evaluation.

---

## 🔧 Features Implemented

* Data Cleaning & Preprocessing
* Feature Engineering (FamilySize, AgeGroup)
* Multiple Machine Learning Models:

  * Logistic Regression
  * Decision Tree
  * Random Forest
* Hyperparameter Tuning using GridSearchCV
* Model Evaluation using multiple metrics
* Feature Importance Analysis

---

## 📊 Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~0.78    |
| Decision Tree       | ~0.75    |
| Random Forest       | ~0.82    |

---

## ⚙️ Best Model

Random Forest performed the best after tuning.

**Best Parameters:**

* n_estimators = 100
* max_depth = 5

## 📈 Evaluation Metrics

* Accuracy: ~0.81
* Precision: ~0.81
* Recall: ~0.70
* F1 Score: ~0.75

Confusion Matrix:

[[93 12]
 [22 52]]

## 📁 Project Structure
Titanic-ML-Optimization/
│── Titanic_ML_Optimization.ipynb
│── README.md

## 🧠 Key Learnings

* Importance of feature engineering
* Comparing multiple machine learning models
* Hyperparameter tuning using GridSearchCV
* Evaluating models using multiple metrics
* Understanding feature importance

## 🚀 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 💡 Conclusion

This project demonstrates a complete end-to-end machine learning workflow, from raw data preprocessing to model optimization and interpretation.

---

## 🔗 Author

Created as part of an internship task to strengthen practical machine learning skills.
