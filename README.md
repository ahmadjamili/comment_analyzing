# 💬 Persian Sentiment Analysis – Food Delivery Comments

This project performs sentiment classification on Persian text comments related to food delivery, using a combination of rule-based labeling and machine learning models.

> 🚀 Submitted on Quera: [https://quera.org/problemset/125361](https://quera.org/problemset/125361)  
> 🏆 Achieved **97.7% F1-score** and **0.976 AUC** using Logistic Regression

---

## 📌 Overview

- Preprocessed and cleaned **56,000+ Persian comments**.
- Removed stopwords and handled character repetitions using regex.
- Applied a **rule-based sentiment scoring system** using the PerSent1 polarity lexicon.
- Labeled each comment as **positive (1)** or **negative (0)** based on word-level polarity.
- Addressed **data imbalance** using undersampling.
- Trained a **Logistic Regression model** on vectorized text data.
- Achieved **high classification accuracy and AUC score**.

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- scikit-learn
- imbalanced-learn (for undersampling)
- CountVectorizer
- Regex for text normalization

