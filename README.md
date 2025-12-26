# Customer-Churn-Prediction

## 📌 Project Overview
This project predicts whether a telecom customer will **churn (leave the service)** or **stay**, using machine learning.  
Businesses can use this model to identify customers likely to leave and take preventive actions.

---

## 📂 Dataset
Dataset used: **Telco Customer Churn Dataset**
- Contains customer details such as:
  - Demographics
  - Contract details
  - Billing information
  - Internet & Phone services
- Target variable → `Churn (Yes / No)`

---

## 🛠 Project Steps
### ✔ 1️⃣ Data Preprocessing
- Handled missing values
- Converted categorical values to numeric
- Replaced values like “No internet service”
- Converted `TotalCharges` to numeric

### ✔ 2️⃣ Feature Engineering
- Created tenure categories
- Applied log transformation on charges
- One-Hot Encoding + Label Encoding

### ✔ 3️⃣ Handling Imbalance
- Used **SMOTE** to balance churn vs non-churn customers

### ✔ 4️⃣ Model Building
Models used:
- Logistic Regression
- XGBoost (with hyperparameter tuning using RandomizedSearchCV)

---

## 📊 Evaluation
Metrics used:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC
