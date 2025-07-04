
markdown
Copy
Edit
# 🎮 Ice Video Game Sales Forecasting

You work for **Ice**, an online store that sells video games globally. To better plan marketing campaigns, the company needs to understand which games are likely to succeed. By analyzing user reviews, expert ratings, genre, platform, ESRB ratings, and historical sales data, this project identifies patterns that help predict game sales.  

This analysis is set in **December 2016** and aims to forecast sales for 2017, simulating real-world planning based on available historical data.

---

## 📌 Project Objective

> **Goal**: Identify patterns that determine a video game’s commercial success.  
> Forecast 2017 game sales using historical data to inform advertising strategy and identify potential bestsellers.

---

## 🗂️ Dataset Description

- Historical sales data up to 2016.
- Features include:
  - Game title
  - Platform (e.g., Xbox, PlayStation)
  - Genre
  - User ratings
  - Expert ratings
  - ESRB age rating (Teen, Mature, etc.)
  - Regional and global sales figures

---

## ⚙️ Methodology

- **Data Cleaning**:
  - Inspected for missing values and duplicates.
  - Standardized categorical variables (platforms, genres, ESRB ratings).
  - Handled missing or anomalous sales entries.
- **Exploratory Data Analysis (EDA)**:
  - Analyzed sales trends by platform and genre.
  - Visualized user and expert rating distributions.
  - Examined ESRB rating impact on sales.
- **Feature Engineering**:
  - Created new features (e.g., total sales, regional ratios).
  - Binned numerical ratings if necessary.
- **Modeling**:
  - Trained regression models to predict game sales.
  - Evaluated models using metrics like RMSE.
  - Validated using train/test splits to simulate future predictions.
- **Business Insights**:
  - Identified platforms and genres with highest sales potential.
  - Highlighted user and expert rating thresholds that predict success.
  - Generated recommendations for 2017 advertising targeting.

---

## 📈 Results

✅ Successfully cleaned and prepared historical sales data.  
✅ Identified strong sales drivers, including platform, genre, and ratings.  
✅ Built predictive models to estimate game sales with acceptable error.  
✅ Provided actionable insights for 2017 marketing campaign planning.

---

## 🛠️ Skills Demonstrated

- Data cleaning and preprocessing with Pandas
- Exploratory Data Analysis (EDA)
- Feature engineering for predictive modeling
- Regression modeling using Scikit-learn
- Model evaluation (RMSE)
- Business-focused recommendations
- Data visualization with Matplotlib/Seaborn
- Jupyter Notebook documentation
- Quick link to project [here](https://github.com/Jolay96/TripleTenProjects-/blob/main/Video%20Game%20Sales%20Forecasting/Video%20Game%20Sales%20Forecasting.ipynb)