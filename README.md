# 🍽️ Restaurant Review Analysis using NLP

## 📌 Project Overview
This project presents a complete **Natural Language Processing (NLP) pipeline** for analyzing restaurant reviews. The objective is to classify customer reviews into sentiment categories using modern deep learning techniques while following an industry-oriented workflow.

The project demonstrates practical implementation of text preprocessing, representation, embeddings, model training, evaluation, and deployment through an interactive user interface.

---

## 🎯 Objectives
- Perform exploratory data analysis (EDA) on real-world text data  
- Apply text preprocessing and representation techniques  
- Learn and visualize word embeddings  
- Train a deep learning–based sentiment analysis model  
- Evaluate model performance using appropriate metrics  
- Deploy the model with an interactive frontend  

---

## 📂 Dataset
- **Name:** Restaurant Reviews  
- **Source:** Kaggle  
- **Format:** TSV  
- **Attributes:**
  - `Review` → Customer review text  
  - `Liked` → Sentiment label (0 = Negative, 1 = Positive)

⚠️ *Note:* The dataset does not include cuisine labels. Any cuisine-related output was intentionally excluded to maintain academic integrity.

---

## 🔍 Exploratory Data Analysis (EDA)
- Displayed dataset head and structure  
- Analyzed sentiment distribution  
- Visualized review length and token distribution  

EDA provided insights into class balance and text characteristics before modeling.

---

## 🧹 Text Preprocessing
The following preprocessing steps were applied:
- Lowercasing  
- Removal of punctuation and special characters  
- Tokenization  

This step ensured consistency and reduced noise in textual data.

---

## 🧠 Text Representation
- Tokenization using **BERT tokenizer**
- Sequence padding and truncation
- Visualization of token length distribution
- Vocabulary size analysis

These steps converted raw text into numerical representations suitable for model input.

---

## 🔗 Word Embeddings
To understand semantic relationships between words, the following embeddings were implemented and visualized
