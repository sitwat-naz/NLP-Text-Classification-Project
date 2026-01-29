# NLP-Text-Classification-Project
Building a Text Classification Pipeline – Word Embedding Exploration
# NLP Text Classification Pipeline – Word Embedding Exploration

## 📌 Project Overview
This project implements a complete Natural Language Processing (NLP) pipeline for text classification.  
The pipeline includes text preprocessing, feature engineering, word embedding exploration, machine learning and deep learning model training, and performance evaluation.

## 🎯 Objective
To classify text data into categories using:
- TF-IDF
- Word Embeddings (Word2Vec)
- Machine Learning and Deep Learning models

## 📂 Dataset
IMDB Movie Reviews Dataset (50,000 labeled reviews)

Source:  
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

## 🧠 Models Implemented
### Machine Learning:
- Logistic Regression (TF-IDF features)

### Deep Learning:
- LSTM Neural Network

## 📊 Results Summary

| Model | Accuracy | Precision | Recall | F1-score |
|--------|----------|-----------|--------|-----------|
| Logistic Regression | 0.8896 | 0.89 | 0.89 | 0.89 |
| LSTM | 0.5015 | 0.50 | 0.50 | 0.41 |

### Conclusion:
Logistic Regression significantly outperformed LSTM on this dataset.  
LSTM showed poor performance due to limited training and lack of hyperparameter tuning.

## 🗂 Folder Structure
