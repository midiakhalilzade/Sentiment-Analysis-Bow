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
<img width="449" height="334" alt="image" src="https://github.com/user-attachments/assets/612d0c99-b55f-4370-ac7b-68f3a33f3d04" />

### CountVectorizer + TF-IDF

* Accuracy: **87.7%**
* Precision: **88.71%**
* Recall: **86.60%**
* F1-score: **87.65%**
<img width="389" height="323" alt="image" src="https://github.com/user-attachments/assets/b53d1de9-ac9d-4ebe-949f-33984aa1a6ff" />

---

## Key Insights

* Manual implementation helps understand how Bag of Words works internally.
* TF-IDF improves feature weighting by reducing the importance of frequent but less meaningful words.
* Both approaches achieve similar performance, showing robustness of classical NLP methods.

---

## Author

* Midia Khalilzade

