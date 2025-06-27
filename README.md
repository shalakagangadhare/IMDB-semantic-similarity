# IMDB-semantic-similarity

# 🎬 NLP Project: Sentiment Analysis on IMDb Movie Reviews

## 📌 Overview

This project focuses on classifying IMDb movie reviews as **positive** or **negative** using Natural Language Processing (NLP) techniques. It combines traditional feature extraction (TF-IDF) and advanced deep learning embeddings (BERT) to evaluate model performance and semantic understanding.

---

## 📁 Dataset

- **Source**: IMDb Large Movie Review Dataset
- **Size**: 50,000 labeled reviews
  - 25,000 for training (balanced)
  - 25,000 for testing
- **Labels**:  
  - `1` = Positive  
  - `0` = Negative  

---

## 🧠 Approach

###  **Text Preprocessing**
- Lowercasing
- Stopword removal
- Tokenization
- Punctuation stripping



---

## 🧪 Results

- **BERT-based embeddings** significantly outperformed traditional TF-IDF and Word2Vec for semantic understanding.
- Models correctly identified reviews with similar sentiment even when word choices differed.

---

## 🔍 Applications
- ✅ Sentiment classification for product/movie reviews
- ✅ Duplicate or paraphrased review detection
- ✅ Chatbot & FAQ intent matching
- ✅ Plagiarism detection in user-generated content
