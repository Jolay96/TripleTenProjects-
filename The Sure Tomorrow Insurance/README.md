# 🛡️ Sure Tomorrow Insurance: Machine Learning Analysis

The **Sure Tomorrow** insurance company wants to leverage machine learning to improve marketing, underwriting, and data privacy. This project explores multiple analytical tasks to evaluate the feasibility of using ML for their operations—from customer segmentation to prediction and data security.

---

## 📌 Project Objectives

> **Goal**: Evaluate the use of machine learning to solve four business-critical tasks for the Sure Tomorrow insurance company:  
> 
> 1️⃣ Find similar customers for marketing.  
> 2️⃣ Predict if a new customer will receive an insurance benefit.  
> 3️⃣ Predict the number of benefits using regression.  
> 4️⃣ Protect personal data with masking without degrading model performance.

---

## 🗂️ Dataset Description

- Customer demographic and behavioral data.
- Features include:
  - Age, gender, income
  - Policy details
  - Number of previously received insurance benefits (target for regression)
- Data requires cleaning and preprocessing before modeling.

---

## ⚙️ Methodology

### **Task 1: Customer Segmentation**

- Used **unsupervised learning** to identify similar customers.
- Employed:
  - Standardization for feature scaling.
  - Clustering algorithms (e.g., KMeans).
- Output:
  - Assigned cluster labels to customers.
  - Enabled targeted marketing strategies.

---

### **Task 2: Classification of Benefit Receipt**

- Goal: Predict whether a new customer will receive an insurance benefit.
- Compared:
  - Trained machine learning model vs. Dummy classifier (untrained baseline).
- Steps:
  - Feature preprocessing and encoding.
  - Trained classifiers (e.g., Logistic Regression).
  - Evaluated using Accuracy, Precision, Recall, F1-Score.
- Analysis:
  - Explained why the trained model outperforms (or may fail to outperform) the dummy model.

---

### **Task 3: Regression Analysis**

- Goal: Predict the number of insurance benefits a customer will receive.
- Used **Linear Regression**:
  - Trained model on customer features.
  - Evaluated with RMSE and MAE metrics.
- Interpretation:
  - Assessed predictive power and usefulness for business planning.

---

### **Task 4: Data Masking (Obfuscation)**

- Designed data transformation algorithm:
  - Applied matrix multiplication to mask personal features.
  - Preserved essential relationships for modeling.
- Validation:
  - Trained regression model on obfuscated data.
  - Verified performance matched unmasked data.
- Outcome:
  - Demonstrated effective privacy protection without degrading model quality.

---

## 📈 Results

✅ Identified customer clusters for targeted marketing.  
✅ Built classification models exceeding dummy baselines.  
✅ Predicted benefit counts using linear regression.  
✅ Designed and validated a data obfuscation algorithm maintaining model performance.

---

## 🛠️ Skills Demonstrated

- Data cleaning and preprocessing with Pandas
- Clustering and unsupervised learning
- Classification modeling and evaluation
- Regression modeling
- Data masking and privacy-preserving transformations
- Scikit-learn and NumPy workflows
- Jupyter Notebook documentation
- Quick link to project [here](https://github.com/Jolay96/TripleTenProjects-/blob/main/The%20Sure%20Tomorrow%20Insurance/The%20Sure%20Tomorrow%20Insurance.ipynb)