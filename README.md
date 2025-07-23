# Stock-Sentiment-Prediction-Using-News-Headlines-with-ML
Applied machine learning models to perform sentiment analysis on financial news headlines to predict stock market trends.


# 📈 Stock Sentiment Prediction Using News Headlines 📰

This project uses machine learning techniques to perform sentiment analysis on financial news headlines and predict their associated stock market sentiment (Positive, Negative, Neutral).

## 🔍 Objective

The goal is to classify news headlines into sentiment categories and analyze how this sentiment can be used to forecast stock market trends. By extracting sentiment from textual data, investors and analysts can make more informed decisions.

## 🧠 Techniques Used

- **Natural Language Processing (NLP)**
- **TF-IDF Vectorization**
- **Supervised Machine Learning**
- **Exploratory Data Analysis (EDA)**

## 📊 Dataset

- Financial news headlines labelled as:
  - `0` → Negative
  - `1` → Positive
  - `2` → Neutral
- Custom-labelled dataset from financial news sources

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK (for stopword removal)
- Matplotlib, Seaborn, WordCloud

## ⚙️ ML Models Evaluated

| Model              | Accuracy | F1 Score (Class 2) |
|--------------------|----------|--------------------|
| Naive Bayes        | 74.54%   | 85%                |
| Logistic Regression| 77.68%   | 86%                |
| **SVM (Best)**     | 77.89%   | **86%**            |

> SVM delivered the best overall performance with high precision for positive and neutral sentiment classes.

## 📈 Exploratory Insights

- Texts with **neutral sentiment** were generally longer.
- Frequent keywords per sentiment:
  - **Negative**: downgrade, cut, decline
  - **Positive**: upgrade, boost, gain
  - **Neutral**: announce, says, confirms

## 📌 Key Features

- Cleaned and preprocessed text using NLP.
- Visualized word frequencies and sentiment distribution using word clouds and bar plots.
- Compared model performance using precision, recall, and F1-score.

## 🔄 Future Work

- Implement deep learning models (LSTM, BERT).
- Include financial indicators like stock prices.
- Use oversampling/undersampling to address class imbalance.

## 📁 Folder Structure

