# 🚕 Sweet Lift Taxi Demand Forecasting

Sweet Lift Taxi company wants to attract more drivers during peak hours by accurately predicting the number of taxi orders for the next hour. This project leverages historical airport taxi order data to build a forecasting model with the goal of keeping the **RMSE on the test set below 48**.

---

## 📌 Project Objective

> **Goal**: Develop a regression model that predicts the hourly number of taxi orders at airports.  
> Ensure that the model's RMSE on the test data is **≤ 48** to enable reliable demand forecasting for better driver allocation.

---

## 🗂️ Dataset Description

- Historical data on hourly taxi orders at airports.
- Features include:
  - Date and time of the order.
  - Lagged demand values to capture temporal patterns.
  - Rolling averages and time-based features (hour of day, day of week).

---

## ⚙️ Methodology

- **Data Preparation**:
  - Resampled time series to hourly intervals.
  - Created lag features to incorporate previous demand values.
  - Engineered rolling means for smoothing trends.
  - Extracted temporal features (hour, day of week) to capture cyclical patterns.
- **Data Splitting**:
  - Divided data into training and test sets while preserving time order.
- **Model Building**:
  - Trained regression models, including:
    - Linear Regression
    - Decision Tree Regressor
    - Random Forest Regressor
  - Tuned hyperparameters to minimize RMSE.
- **Evaluation**:
  - Computed RMSE on validation and test sets.
  - Selected model with RMSE ≤ 48 on the test data.

---

## 📈 Results

✅ Successfully cleaned and prepared time series data.  
✅ Engineered meaningful lag and rolling features to improve predictive power.  
✅ Built models achieving RMSE ≤ 48 on the test set.  
✅ Provided a reliable solution to help Sweet Lift optimize driver allocation during peak demand hours.

---

## 🛠️ Skills Demonstrated

- Time series data preprocessing with Pandas
- Feature engineering (lags, rolling averages, time-based variables)
- Regression modeling with Scikit-learn
- Model evaluation using RMSE
- Business problem framing for demand forecasting
- Jupyter Notebook documentation
- Quick Link to project [here](https://github.com/Jolay96/TripleTenProjects-/blob/main/Sweet%20Lift%20Taxi%20Company/Sweet%20Lift%20Taxi%20Company.ipynb)
