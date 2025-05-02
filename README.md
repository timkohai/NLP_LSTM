# 🧠 Sentiment Analysis with LSTM and GloVe

This project performs binary sentiment classification (positive/negative) on product reviews using deep learning with TensorFlow/Keras. It leverages pre-trained GloVe word embeddings and an LSTM-based architecture.

---

## 🚀 Features

- Text preprocessing with:
  - HTML removal
  - Contraction expansion
  - Stopword removal
  - Lemmatization / optional stemming
  - Spell correction (SymSpell or pyspellchecker)
- Pre-trained GloVe embeddings
- Bidirectional LSTM model
- Early stopping and learning rate scheduling
- Stratified train/val/test split by category + label
- Support for real-time prediction on new text input

---

## 🗃️ Dataset

Downloaded from:
- http://www.cs.jhu.edu/~mdredze/datasets/sentiment/domain_sentiment_data.tar.gz  
Includes reviews from:
- `books`, `dvd`, `electronics`, `kitchen_&_housewares`

Also includes unlabeled reviews for semi-supervised tasks (optional).

---

## 📦 Installation


