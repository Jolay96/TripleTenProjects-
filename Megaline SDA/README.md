# 📞 Megaline Prepaid Plan Revenue Analysis

As an analyst at telecom operator Megaline, this project aims to help the commercial department determine which of their two prepaid plans—**Surf** or **Ultimate**—brings in more revenue. By analyzing usage data from 500 customers in 2018, the company can optimize its advertising budget to promote the more profitable plan.

---

## 📌 Project Objective

> **Goal**: Analyze customer behavior and calculate revenue for Surf and Ultimate prepaid plans.  
> Identify which plan generates higher revenue to inform marketing and advertising strategy.

---

## 🗂️ Dataset Description

- 500 Megaline clients
- Includes:
  - Customer demographic data
  - Region
  - Plan type (Surf or Ultimate)
  - Number of calls made and texts sent in 2018
  - Data usage in MB
- **Important rounding rules**:
  - Calls: Rounded up per call to the nearest minute.
  - Data: Monthly total rounded up to the nearest GB.

---

## 💰 Plan Pricing Details

**Surf**:
- $20 monthly fee
- Included: 500 minutes, 50 texts, 15 GB
- Overages:
  - 3 cents per extra minute
  - 3 cents per extra text
  - $10 per extra GB

**Ultimate**:
- $70 monthly fee
- Included: 3000 minutes, 1000 texts, 30 GB
- Overages:
  - 1 cent per extra minute
  - 1 cent per extra text
  - $7 per extra GB

---

## ⚙️ Methodology

- **Data Preparation**:
  - Loaded and inspected data for missing values and data types.
  - Applied rounding rules for call minutes and data usage.
- **Revenue Calculation**:
  - Calculated monthly overages for calls, texts, and data.
  - Applied pricing rules to compute total revenue per user.
- **Analysis**:
  - Aggregated revenue by plan.
  - Compared average and total revenue between Surf and Ultimate plans.
  - Visualized plan distributions and revenue metrics.
- **Conclusion**:
  - Identified the plan generating higher revenue on average.
  - Recommended focus area for advertising budget.

---

## 📈 Results

✅ Successfully cleaned and prepared data with correct rounding rules.  
✅ Calculated accurate per-customer revenue for both plans.  
✅ Determined which plan brings in more revenue.  
✅ Provided actionable insight for targeted marketing.

---

## 🛠️ Skills Demonstrated

- Data cleaning and preprocessing with Pandas
- Business logic implementation (rounding and pricing rules)
- Revenue calculation and aggregation
- Data visualization with Matplotlib
- Statistical comparison of plan revenue
- Jupyter Notebook documentation
- Quick link to project [Here](https://github.com/Jolay96/TripleTenProjects-/blob/main/Megaline%20SDA/Megaline%20SDA.ipynb)
