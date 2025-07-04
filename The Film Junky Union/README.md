# 🎬 The Film Junky Union: Movie Review Sentiment Classification

The **Film Junky Union** is a new, edgy community for classic movie enthusiasts that aims to improve discussions by filtering out negative reviews. This project develops a natural language processing (NLP) model that can automatically detect negative reviews in movie commentary. Using a labeled IMDB reviews dataset, the model classifies text as **positive** or **negative**, with the goal of reaching an **F1 score of at least 0.85**.

---

## 📌 Project Objective

> **Goal**: Train a text classification model to accurately identify negative IMDB movie reviews.  
> Achieve an F1 score ≥ 0.85 to ensure reliable automated moderation for the Film Junky Union community platform.

---

## 🗂️ Dataset Description

- IMDB movie reviews dataset with polarity labels:
  - Review text
  - Label: **positive** or **negative**
- Used for supervised binary classification.

---

## ⚙️ Methodology

- **Data Cleaning and Preparation**:
  - Removed duplicates and irrelevant characters.
  - Standardized text (lowercasing, removing punctuation).
- **Text Preprocessing**:
  - Tokenization
  - Lemmatization or stemming
  - Stop word removal
  - Vectorization using TF-IDF
- **Model Training**:
  - Split data into training and test sets.
  - Trained classification algorithms including:
    - Logistic Regression
    - Naive Bayes
    - Support Vector Machine (SVM)
  - Tuned hyperparameters for best performance.
- **Evaluation**:
  - Measured model performance using:
    - Accuracy
    - Precision
    - Recall
    - F1-score (target ≥ 0.85)
  - Selected best-performing model for deployment.
- **Validation**:
  - Tested model on unseen data to verify generalization.

---

## 📈 Results

✅ Successfully cleaned and preprocessed IMDB review text.  
✅ Built and compared multiple classification models.  
✅ Achieved F1 score ≥ 0.85 on the test set.  
✅ Delivered a reliable system for automatically filtering negative reviews to improve community discussions.

---

## 🛠️ Skills Demonstrated

- Natural Language Processing (NLP) workflows
- Text cleaning and preprocessing with NLTK / SpaCy
- Feature extraction using TF-IDF
- Supervised classification modeling with Scikit-learn
- Model evaluation with F1-score, Precision, Recall
- Jupyter Notebook documentation
- Quick Link to project [here](https://github.com/Jolay96/TripleTenProjects-/blob/main/The%20Film%20Junky%20Union/The%20Film%20Junky%20Union.ipynb)