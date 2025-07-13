# Fake-New-Detection-
Here’s a professional and informative **README description** you can add to your GitHub repository for the **Fake News Detection using LSTM and Word Embeddings** project:

# 📰 Fake News Detection using LSTM and GloVe Embeddings

This project aims to detect fake news articles using deep learning techniques — specifically Long Short-Term Memory (LSTM) networks and pre-trained GloVe word embeddings. It is part of an academic research initiative conducted at R.N.G. Patel Institute of Technology.

## 📌 Project Overview

With the rise of misinformation across digital platforms, detecting fake news has become a crucial task. This project utilizes:

* **LSTM neural networks** for sequential learning
* **Pre-trained GloVe embeddings** for semantic text representation
* **Text preprocessing** (lowercasing, stopword removal, tokenization, etc.)
* **Binary classification** of news articles as real or fake

## 🧠 Technologies Used

* Python
* TensorFlow / Keras
* GloVe Word Embeddings (100d)
* NLTK
* Pandas, NumPy
* Matplotlib for visualization
* Jupyter Notebook

## 📊 Dataset

The dataset used was sourced from Kaggle:
🔗 [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
It contains over 14,000 labeled news articles with title, author, content, and labels (fake or real).

## 📈 Model Summary

* **Embedding Layer**: Loaded with 100-dimensional GloVe vectors
* **LSTM Layer**: 128 units for sequential learning
* **Dropout**: Regularization to prevent overfitting
* **Dense Output**: Sigmoid activation for binary classification
* **Accuracy**: \~53% on validation data

> ⚠️ Note: While the model accuracy is modest, this project serves as a strong foundation and learning experience. Future work includes trying transformer models like BERT and expanding the dataset.

## 🧑‍💻 Contributors

* [**Riddhi Mistry**](https://github.com/riddhimistry141)
* [**Vishwa Lad**](https://github.com/your-friend-github-handle-here)

## 📄 Research Paper

This project was presented in an IEEE-style research format. PDF available in the repository.

## 🚀 Future Work

* Integrate contextual embeddings (e.g., BERT, RoBERTa)
* Experiment with ensemble models
* Tune hyperparameters for better accuracy
* Explore more diverse and balanced datasets
