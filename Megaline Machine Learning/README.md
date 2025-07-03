# 📱 Megaline Plan Recommendation Model

Megaline, a mobile carrier, discovered that many customers still use outdated legacy plans. To help them modernize their offerings and improve customer satisfaction, they want to recommend one of their newer plans—**Smart** or **Ultra**—to existing users.  

This project develops a classification model to analyze subscriber behavior and recommend the most suitable new plan. The ultimate goal is to reach a model accuracy of at least **0.75** on the test set.

---

## 📌 Project Objective

> **Goal**: Build and evaluate a classification model that predicts whether a customer should be recommended the Smart or Ultra plan based on their usage behavior.  
> Aim for the highest possible accuracy, with a minimum threshold of **0.75**.

---

## 🗂️ Dataset Description

- Behavior data for Megaline subscribers who have already switched to new plans.  
- Features include:
  - Call minutes
  - Text messages sent
  - Internet data usage
  - Demographic and account features
- Target variable:
  - Plan recommendation (Smart or Ultra)

---

## ⚙️ Methodology

- **Preprocessing**:
  - Data cleaning and preparation was performed previously in the Statistical Data Analysis course.
  - Focused here entirely on model development.
- **Model Development**:
  - Split data into training and test sets.
  - Trained multiple classification models, including:
    - Decision Tree Classifier
    - Random Forest Classifier
    - Logistic Regression
  - Tuned hyperparameters for best performance.
- **Evaluation**:
  - Measured accuracy on validation and test sets.
  - Selected best-performing model meeting or exceeding the 0.75 accuracy threshold.

---

## 📈 Results

✅ Successfully built a classification model achieving accuracy ≥ 0.75 on the test set.  
✅ Recommended the best-performing model for deployment to support sales and marketing teams.  
✅ Enabled targeted recommendations to help subscribers choose the optimal modern plan.

---

## 🛠️ Skills Demonstrated

- Supervised classification modeling
- Model selection and hyperparameter tuning
- Accuracy evaluation on test data
- Use of Scikit-learn for machine learning workflows
- Jupyter Notebook documentation
- Quick link to project [here](https://github.com/Jolay96/TripleTenProjects-/blob/main/Megaline%20Machine%20Learning/Megaline%20Machine%20Learning.ipynb)