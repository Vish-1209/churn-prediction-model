# 🔄 Customer Churn Prediction

## 📌 Overview

This project predicts whether a bank customer will **churn (exit)** or not using historical data. It is a **binary classification** problem that helps banks retain customers by identifying those at risk.

---


## 🧠 Objective

To build a machine learning model that estimates the **probability of churn** and helps the bank understand key churn indicators.

---

## 🧰 Tools & Techniques Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Logistic Regression, SVM, Random Forest, XGBoost)
- SMOTE (for handling class imbalance)
- Feature Importance, SMOTE
- Classification Evaluation: F1 Score, Precision, Recall, ROC Curve

---

## 📊 Dataset

- Source: Provided as `Churn_Modelling.csv`
- 10,000+ customers
- Features include age, balance, credit score, geography, tenure, etc.
- Target variable: `Exited` (1 = Churned, 0 = Not churned)

---

## 🔍 Key Steps

1. **Data Cleaning**  
   - Encoded categorical features

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions and relationships
   - Identified churn trends by age, balance, credit score

3. **Feature Engineering**  
   - Removed irrelevant columns (RowNumber, CustomerId, Surname)
   - Applied SMOTE for balancing

4. **Modeling & Evaluation**  
   - Trained 4 models: Logistic Regression, SVC, XGBoost, Random Forest
   - Evaluated using F1-score, Confusion Matrix, ROC-AUC

---

## 🏆 Results

- Best model: **Random Forest Classifier**
- Accuracy: `~86%`
- F1 Score: `0.82`
- Most important features: **Age**, **Balance**, **Credit Score**

---

## 📈 Visualizations

- Churn distribution
- Feature importance bar plots
- ROC Curve for model comparison

---

## 🚀 Future Improvements

- Deploy model using **Streamlit** or **Flask**
- Add SHAP for explainability
- Test on real-time data with dashboards

---

## 📁 Files Included

| File Name             | Description                        |
|----------------------|------------------------------------|
| `Bank_Churn.ipynb`   | Main notebook with full pipeline   |
| `Churn_Modelling.csv`| Dataset used for training/testing  |
| `README.md`           | Project documentation              |

---

## 📬 Contact

**Vishruti Karia**  
📧 Email: kariavish12@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/vishruti-karia-4839641a1)

---

*Thanks for checking out this project! Feedback & collaboration welcome.*

