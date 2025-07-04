# 🚗 Rusty Bargain: Used Car Price Prediction

Rusty Bargain, a used car sales service, is developing an app that helps customers quickly find the market value of their car. By analyzing historical sales data—including technical specs, trim versions, and prices—this project aims to build a model that accurately predicts used car prices. The business requires a solution that balances **prediction quality**, **speed**, and **training time** for real-world deployment.

---

## 📌 Project Objective

> **Goal**: Develop a regression model that predicts the market value of used cars with high accuracy.  
> Optimize the model for both **prediction speed** and **training time**, making it practical for integration into Rusty Bargain's customer app.

---

## 🗂️ Dataset Description

- Historical data on used car sales.  
- Features include:
  - Technical specifications (e.g., engine size, power, mileage)
  - Trim/version details
  - Vehicle age
  - Price (target variable)
- Data requires cleaning and preprocessing before modeling.

---

## ⚙️ Methodology

- **Data Cleaning**:
  - Handled missing values and duplicates.
  - Verified data types and corrected inconsistencies.
- **Feature Engineering**:
  - Selected meaningful predictors of car price.
  - Encoded categorical variables where necessary.
- **Model Building**:
  - Trained multiple regression models, including:
    - Linear Regression
    - Decision Tree Regressor
    - Random Forest Regressor
  - Compared models based on:
    - Prediction quality (RMSE)
    - Prediction latency (speed)
    - Training time
- **Evaluation**:
  - Split data into training and validation sets.
  - Computed RMSE on validation data.
  - Measured time required for training and prediction.
- **Selection**:
  - Chose the model offering the best balance of accuracy, speed, and efficiency.

---

## 📈 Results

✅ Successfully cleaned and prepared the used car dataset.  
✅ Built and compared multiple regression models.  
✅ Identified the best-performing model in terms of accuracy, prediction speed, and training time.  
✅ Recommended an optimal model for app integration.

---

## 🛠️ Skills Demonstrated

- Data cleaning and preprocessing with Pandas
- Feature engineering and selection
- Regression modeling using Scikit-learn
- Model evaluation with RMSE
- Measuring training time and prediction latency
- Data visualization with Matplotlib
- Jupyter Notebook documentation
- Quick link to the project [here](https://github.com/Jolay96/TripleTenProjects-/blob/main/Rusty%20Bargain%20Used%20Car%20Sales/Rusty%20Bargain%20Used%20Car%20Sales.ipynb)