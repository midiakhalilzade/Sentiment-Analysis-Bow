# Sentiment Analysis using Bag of Words

## Overview

This project focuses on sentiment analysis of text comments (positive vs. negative) using the **Bag of Words (BoW)** technique.

Two different implementations are provided:

1. A **manual implementation** of Bag of Words
2. A **library-based implementation** Scikit-learn based feature extraction (CountVectorizer / TF-IDF)

The goal is to compare performance and understand how feature extraction methods impact model results.

---

## Technologies & Libraries
* PyTorch (model building and training)
* NumPy
* Pandas
* Scikit-learn (preprocessing, evaluation metrics)
* Matplotlib (visualization)

---
## Model

A neural network model (MLP) is implemented using PyTorch:

* Input: Bag of Words vectors
* Hidden layers: Fully connected layers
* Output: Binary classification (positive / negative)
* Loss function: CrossEntropyLoss
* Optimizer: Adam / SGD

---
## Results

### Manual Bag of Words

* Accuracy: **87.72%**
* Precision: **88.16%**
* Recall: **87.36%**
* F1-score: **87.76%**

### CountVectorizer + TF-IDF

* Accuracy: **87.7%**
* Precision: **88.71%**
* Recall: **86.60%**
* F1-score: **87.65%**

---

## Key Insights

* Manual implementation helps understand how Bag of Words works internally.
* TF-IDF improves feature weighting by reducing the importance of frequent but less meaningful words.
* Both approaches achieve similar performance, showing robustness of classical NLP methods.

---

## Author

* Midia Khalilzade

