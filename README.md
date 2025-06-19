# 💬 Twitter Sentiment Analysis

This project implements a machine learning pipeline to classify tweets as positive or negative using the Sentiment140 dataset. The analysis includes data cleaning, feature extraction, model training, and evaluation using logistic regression.

## 🗂 Project Overview

- 🔎 Dataset: Sentiment140 (160,000 tweets labeled as positive/negative)
- 🧹 Preprocessing: Lowercasing, stopword removal, stemming
- 🧠 Model: Logistic Regression
- 📈 Evaluation: Accuracy score on test data

## 📦 Dataset Source

- Source: [Sentiment140 on Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)
- Data format: CSV file with tweet text and sentiment labels
- Accessed via Kaggle API

## 🛠️ Technologies Used

- Python 3
- Pandas, NumPy
- NLTK (stopwords, stemming)
- Scikit-learn (TF-IDF vectorizer, Logistic Regression)
- Kaggle API for dataset download
