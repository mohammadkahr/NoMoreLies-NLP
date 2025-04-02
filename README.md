# 📰 Fake News Detector

A NLP project to classify real and fake news articles.

## 📌 Project Overview
This project aims to detect fake news using natural language processing (NLP) techniques. The dataset consists of two CSV files:
- `True.csv` → Contains real news
- `Fake.csv` → Contains fake news

The model is trained to classify news articles as either **real** (1) or **fake** (0).

## 📂 Dataset Preparation
1. Load both datasets.
2. Label them (`1` for real, `0` for fake).
3. Merge and shuffle the data.
4. Preprocess the text (cleaning, stopword removal, tokenization).
5. Convert text to numerical representations (TF-IDF, word embeddings, etc.).


## 🏗 Model Training
The project implements various ML models, such as:
- Logistic Regression
- Support Vector Machines (SVM)
- Neural Networks (LSTM, BERT)

Evaluation metrics include accuracy, precision, recall, and F1-score.

## 📊 Results & Performance
The trained model is evaluated using:
- **Confusion Matrix**
- **Classification Report**
- **ROC Curve**


