# NLP_Disaster_Tweets_Kaggle
This project builds a machine learning system to determine whether a tweet refers to a real disaster or not. The dataset comes from the Kaggle competition “Natural Language Processing with Disaster Tweets” and includes 7,613 labeled tweets and 3,263 test tweets. The task is to classify each tweet as disaster-related (1) or not a disaster (0).

📊 Project Overview

The notebook includes:

Exploratory Data Analysis (EDA)

Text preprocessing: cleaning, normalization, tokenization

Feature engineering using keywords and text length

Modeling approaches:

TF–IDF + Logistic Regression (classical baseline)

Bidirectional LSTM (BiLSTM) neural network for learned embeddings

Evaluation metrics: accuracy, F1-score, and confusion matrix analysis

Kaggle submission files

🎯 Objective

The goal is both to build an accurate classifier and to compare two major NLP strategies:

Hand-engineered features (TF–IDF n-grams + Logistic Regression)

Deep learning representations (BiLSTM sequence model)

This comparison highlights the strengths and limitations of classical vs. neural approaches for real-time disaster tweet classification.

📎 Dataset

Kaggle Competition:
https://www.kaggle.com/competitions/nlp-getting-started/data
<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/ee07878d-b77d-4b3d-988f-42beff93825c" />
