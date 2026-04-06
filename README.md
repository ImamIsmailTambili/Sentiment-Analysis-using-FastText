# 🤖 Sentiment Analysis using FastText

This project is a sentiment analysis system that classifies user reviews into **positive, negative, and neutral** categories using FastText.

---

## 🚀 Features

- Scraping real-world data from app reviews  
- Data preprocessing (cleaning, tokenization, stemming)  
- Sentiment labeling based on rating  
- Data augmentation to handle class imbalance  
- FastText model training  
- Model evaluation using Accuracy, Precision, Recall, and F1-score  
- REST API for real-time prediction using FastAPI  

---

## 🏗️ Tech Stack

### Machine Learning
- FastText  
- Scikit-learn  
- Pandas  
- NLTK  
- Sastrawi  

### Backend API
- FastAPI  
- SQLAlchemy  
- SQLite  

---

## 🔍 Workflow

1. Data Collection (Google Play Scraper)  
2. Data Cleaning & Preprocessing  
3. Tokenization & Stemming  
4. Data Augmentation  
5. Train/Test Split  
6. Model Training (FastText)  
7. Evaluation  
8. Deployment via API  

---

## 📊 Model Performance

| Model                | Accuracy |
|---------------------|----------|
| Without Augmentation| 86%      |
| With Augmentation   | 92%      |

---

## 🔗 Google Colab

You can run the full machine learning pipeline here:

👉 **[Open Google Colab](https://colab.research.google.com/drive/1aJ6rScWt96Uf6GYUnlLmDdcwOPXfGLaz?usp=sharing)**
