# 🛢️ OilyGiant: Oil Well Location Selection and Profit Analysis

As a data scientist at **OilyGiant Mining Company**, your mission is to help identify the best location for drilling a new oil well. By analyzing oil well parameters across three regions, you’ll build a predictive model to estimate reserves, rank potential wells, and determine which region offers the highest total profit while accounting for uncertainty and risk.

---

## 📌 Project Objective

> **Goal**: Build a model that predicts oil reserves in new wells and select the region with the highest potential profit.  
> Use statistical analysis to evaluate and compare regions, accounting for profit variability and investment risk.

---

## 🗂️ Dataset Description

- Data on oil samples from three regions.
- For each well:
  - Parameters describing oil quality.
  - Known volume of reserves (target variable).
- Each region contains many wells for model training and evaluation.

---

## ⚙️ Methodology

- **Data Exploration**:
  - Inspected and visualized oil well parameters.
  - Compared data distributions across regions.
- **Model Building**:
  - Built regression models (Linear Regression) to predict reserve volume.
  - Trained and validated on regional datasets.
- **Well Selection**:
  - Predicted reserve volumes in each region.
  - Selected top oil wells with highest estimated reserves.
- **Profit Calculation**:
  - Modeled revenue and costs.
  - Calculated potential profit for each region based on selected wells.
- **Risk Analysis**:
  - Used the **Bootstrapping** technique to simulate profit distributions.
  - Estimated average profit, confidence intervals, and risk of losses.
- **Recommendation**:
  - Chose the region with the highest expected profit and acceptable risk profile.

---

## 📈 Results

✅ Built regression models predicting reserves for new wells.  
✅ Identified top-performing wells in each region.  
✅ Simulated profit distributions using bootstrapping.  
✅ Determined the region with the highest expected profit and lowest risk of loss.  
✅ Provided clear recommendation for the new well location.

---

## 🛠️ Skills Demonstrated

- Data cleaning and exploration with Pandas
- Regression modeling with Scikit-learn
- Statistical simulation using Bootstrapping
- Profit and risk analysis
- Data visualization with Matplotlib
- Business-oriented analytical thinking
- Jupyter Notebook documentation
- Quick link to project [here](https://github.com/Jolay96/TripleTenProjects-/blob/main/OilyGiantMiningCompany/OilyGiantMiningCompany.ipynb)