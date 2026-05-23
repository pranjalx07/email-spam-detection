# 📧 Spam Email Classifier

A machine learning pipeline that classifies text messages/emails as **spam** or **ham (not spam)** using Natural Language Processing and a Naive Bayes classifier.

---

## 📌 Overview

This project builds a text classification model trained on a labelled spam/ham dataset. It covers the full ML workflow — from data cleaning and exploratory analysis to model training, evaluation, and inference.

---

## 🗂️ Dataset

The project uses `spam_ham_dataset.csv`, a labelled dataset with two classes:

| Label | Meaning |
|-------|---------|
| `ham` | Legitimate message |
| `spam` | Unwanted/junk message |

---

## 🔧 Tech Stack

- **Python 3**
- [pandas](https://pandas.pydata.org/) — data manipulation
- [NumPy](https://numpy.org/) — numerical operations
- [scikit-learn](https://scikit-learn.org/) — ML pipeline, TF-IDF, Naive Bayes
- [matplotlib](https://matplotlib.org/) & [seaborn](https://seaborn.pydata.org/) — visualizations
