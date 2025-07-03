# 🏭 Gold Recovery Prediction from Ore Processing

This project focuses on predicting the efficiency of gold recovery from ore at a mining company’s flotation plant. The goal is to build a regression model that accurately predicts recovery rates using process parameters, while carefully validating and cleaning the raw data extracted from the warehouse.

---

## 📌 Project Objective

> **Goal**: Develop a predictive model to estimate gold recovery efficiency based on production parameters.  
> Ensure thorough data validation and cleaning before modeling, given raw warehouse data with differences between training and test sets.

---

## 🗂️ Data Description

- **gold_recovery_train.csv** — Training dataset with features and target.  
- **gold_recovery_test.csv** — Test dataset (features only, no target).  
- **gold_recovery_full.csv** — Combined source data with all features.  
- Data is indexed by **date and time** (the `date` feature), and parameters close in time may be correlated.
- Some features present in training may be missing in testing because of delayed measurements or calculations.

---

## ⚙️ Methodology

- **Data Inspection and Cleaning**:
  - Verified raw warehouse data consistency.
  - Identified and addressed missing values.
  - Ensured no data leakage by aligning training and testing features.
- **Feature Engineering**:
  - Selected shared features between train and test sets.
  - Created and compared feature sets for modeling.
- **Model Building**:
  - Trained regression models using Scikit-learn, including:
    - Decision Tree Regressor
    - Random Forest Regressor
  - Used the training set to fit models, avoiding target features absent in the test set.
- **Evaluation**:
  - Calculated Mean Absolute Error (MAE) to assess prediction quality.
  - Compared models on test-like splits to choose the best approach.

---

## 📈 Results

✅ Successfully cleaned and aligned training and test datasets.  
✅ Built regression models that predicted gold recovery efficiency with low MAE.  
✅ Recommended the best-performing model for operational use.

---

## 🛠️ Skills Demonstrated

- Data cleaning and preprocessing with Pandas
- Handling missing features between train/test sets
- Feature selection
- Regression modeling (Decision Tree, Random Forest)
- Model evaluation using MAE
- Jupyter Notebook documentation
- Quick link to the project [here](https://github.com/Jolay96/TripleTenProjects-/blob/main/Gold%20Recovery/Gold%20Recovery.ipynb)