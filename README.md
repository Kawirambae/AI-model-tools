# 🧠 AI Model Tools

This repository contains machine learning and deep learning models built and tested using Google Colab, as part of an AI development module. It includes classical ML, deep learning, and NLP tasks, with hands-on implementation and ethical considerations.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/loisekawira/AI-model-tools/blob/main/AImodel.ipynb)

---

## 📁 Contents

### 🔹 `AImodel.ipynb`
An all-in-one Colab notebook containing:
- ✅ Task 1: Classical ML using Scikit-learn (Iris dataset, Decision Tree)
- ✅ Task 2: Deep Learning using TensorFlow (MNIST CNN classifier)
- ✅ Task 3: NLP with spaCy (NER + sentiment analysis on Amazon reviews)

---

## ✅ Tasks Overview

### 📌 Task 1: Classical Machine Learning
- Dataset: Iris species
- Tools: Scikit-learn
- Goal: Preprocess data, train Decision Tree classifier, evaluate accuracy, precision, recall

### 📌 Task 2: Deep Learning
- Dataset: MNIST handwritten digits
- Tools: TensorFlow/Keras
- Goal: Build a CNN model, achieve >95% accuracy, visualize 5 predictions

### 📌 Task 3: NLP with spaCy
- Dataset: Amazon product reviews
- Goal: Perform Named Entity Recognition (NER) and rule-based sentiment analysis
- Tools: spaCy, TextBlob

---

## ⚖️ Ethical Considerations
- 📉 Biases in datasets (e.g., MNIST handwriting, review sentiment interpretation)
- 🛠️ Mitigated using rule-based NLP tweaks and TensorFlow Fairness Indicators

---

## 🚀 How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com)
2. Run each section: preprocessing, model training, evaluation, and analysis
3. GPU acceleration available via Colab runtime settings

---

## 🛠 Requirements

Colab comes pre-installed with most dependencies. If running locally:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow spacy textblob
python -m textblob.download_corpora
python -m spacy download en_core_web_sm
