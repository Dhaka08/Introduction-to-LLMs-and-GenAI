# NLP Sentiment Analysis Projects

[![Python](https://img.shields.io/badge/python-3.11-blue)]()  ![License](https://img.shields.io/badge/license-MIT-green)

## Overview
These mini projects focus on **analyzing customer reviews** in the e-commerce domain to understand and predict customer sentiment.  
With the rapid growth of online platforms and increasing user feedback, businesses need AI-driven solutions to monitor sentiment, prevent customer churn, protect brand reputation, and optimize revenue.

The projects demonstrate essential NLP workflows, from **text cleaning and vectorization** to **word embeddings** using Word2Vec and GloVe.

---

## Mini Project 1: Basics of NLP – Text Cleaning & Vectorization

### Problem Statement
Manually analyzing thousands of customer reviews is time-consuming and unsustainable.  
The goal of this project is to preprocess textual data and build a predictive model to classify customer sentiment as **positive, negative, or neutral**.

### Features
- Text cleaning and preprocessing (removing noise, stopwords, punctuation)  
- Tokenization and vectorization of customer reviews  
- Sentiment classification using machine learning models  

### Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- NLTK / SpaCy

### How to Run
1. Clone the repository:  
   ```bash
   git clone <repository-url>
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the notebook:
   ```bash
   jupyter notebook MiniProject1_TextCleaning_Vectorization.ipynb

## Mini Project 2: Word2Vec & GloVe Embeddings

### Problem Statement
To capture semantic meaning and relationships between words in customer reviews, this project uses **Word2Vec** and **GloVe embeddings** for better sentiment analysis performance.

### Features
- Building Word2Vec and GloVe embeddings from customer reviews  
- Visualizing word vectors and semantic similarities  
- Applying embeddings to sentiment classification tasks  

### Tech Stack
- Python  
- Gensim, SpaCy  
- Matplotlib / Seaborn  
- Scikit-learn
  

### How to Run
1. Clone the repository:  
   ```bash
   git clone <repository-url>
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the notebook:
   ```bash
   jupyter notebook MiniProject2_Word2Vec_GloVe.ipynb
