# 🏦 Beta Bank Customer Churn Prediction

Predicting customer churn is critical for banks aiming to reduce costs and improve customer retention. Beta Bank faces steady customer losses each month and wants to identify which clients are likely to leave. By anticipating churn, the bank can proactively engage these customers with targeted retention offers.

This project uses historical customer behavior data to build a classification model that predicts whether a customer will terminate their relationship with the bank.

---

## 📌 Project Objective

> **Goal**: Build a predictive model with the highest possible F1 score (minimum target: 0.59).  
> Also evaluate the model using the AUC-ROC metric and compare it to the F1 score.

---

## 🗂️ Dataset Description

- Client behavior and contract history data.
- Features include demographics, account tenure, balance changes, and transaction history.
- Target variable: whether the client closed their account (churn = 1) or remained (churn = 0).

---

## ⚙️ Methodology

- **Data Cleaning**: Inspected for missing values and corrected data types.
- **EDA**: Analyzed class imbalance and feature distributions.
- **Feature Engineering**: Selected relevant predictors and addressed categorical variables.
- **Train/Test Split**: Divided data into training and testing sets.
- **Modeling**: Trained multiple classification models, including:
  - Decision Tree Classifier
  - Random Forest Classifier
- **Class Imbalance Handling**:
  - Used `class_weight='balanced'`
- **Evaluation**:
  - Computed F1 score on validation and test sets.
  - Measured AUC-ROC and compared to F1 to assess model discrimination capability.

---

## 📈 Results

✅ Achieved F1 score ≥ 0.59 on the test set.  
✅ Evaluated AUC-ROC to confirm the model's ranking performance.  
✅ Recommended best-performing model based on balance between F1 and AUC-ROC.

---

## 🛠️ Skills Demonstrated

- Data preprocessing (Pandas, NumPy)
- Exploratory Data Analysis (EDA)
- Feature engineering
- Classification modeling with Scikit-learn
- Handling imbalanced classes
- Model evaluation (Accuracy, F1, AUC-ROC)
- Jupyter Notebook documentation
- Quick Link to Project [here](https://github.com/Jolay96/TripleTenProjects-/blob/main/Beta%20Bank%20Supervised%20Learning/Beta%20Bank%20Supervised%20Learning.ipynb)
