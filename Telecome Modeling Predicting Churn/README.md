# 📞 Interconnect Telecom Client Churn Prediction

Interconnect is a telecom operator that wants to proactively reduce customer churn by offering targeted promotions and special plan options. By building a churn prediction model, the company can identify at-risk customers early and take action to retain them.  

This project uses customer demographic, contract, and service usage data to train a classification model predicting churn risk.

---

## 📌 Project Objective

> **Goal**: Develop a machine learning model that predicts whether a customer is likely to churn.  
> Enable the marketing team to target at-risk users with promotional offers to reduce overall churn.

---

## 🗂️ Dataset Description

- Customer demographic data
- Contract details:
  - Monthly, 1-year, or 2-year contracts
  - Payment method
  - Electronic billing
- Service usage features:
  - Landline connections
  - Internet type (DSL or fiber optic)
  - Optional services such as:
    - OnlineSecurity
    - DeviceProtection
    - TechSupport
    - OnlineBackup
    - StreamingTV
    - StreamingMovies
- Target variable: **Churn** (yes/no)

---

## ⚙️ Methodology

- **Data Preparation**:
  - Merged multiple data files (personal, contract, internet, phone).
  - Checked for missing values and duplicates.
  - Encoded categorical variables.
  - Created binary target label (Churn = 1 if customer ended service).
- **Exploratory Data Analysis (EDA)**:
  - Analyzed churn rates by contract type, payment method, and optional services.
  - Identified important features affecting churn risk.
- **Feature Engineering**:
  - Selected relevant features for modeling.
  - Addressed class imbalance using appropriate strategies.
- **Model Building**:
  - Trained classification models including:
    - Logistic Regression
    - Decision Tree
    - Random Forest
  - Used cross-validation for robust performance estimates.
- **Evaluation**:
  - Measured model accuracy, F1-score, and ROC-AUC.
  - Selected best model based on balanced classification metrics.

---

## 📈 Results

✅ Successfully cleaned and merged complex customer data.  
✅ Built classification models predicting churn with strong F1 and ROC-AUC scores.  
✅ Identified high-risk customer segments for targeted retention campaigns.  
✅ Provided actionable insights to reduce churn and increase customer lifetime value.

---

## 🛠️ Skills Demonstrated

- Data cleaning and merging with Pandas
- Feature engineering and encoding
- Handling class imbalance
- Supervised classification with Scikit-learn
- Model evaluation (Accuracy, F1, ROC-AUC)
- Business problem framing for churn reduction
- Jupyter Notebook documentation
- Quick link to project [here](https://github.com/Jolay96/TripleTenProjects-/blob/main/Telecome%20Modeling%20Predicting%20Churn/Telecom%20Modeling%20Predicting%20Churn%20project.ipynb)