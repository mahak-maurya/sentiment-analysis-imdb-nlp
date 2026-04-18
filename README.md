# sentiment-analysis-imdb-nlp
# 🎬 Sentiment Analysis using NLP — IMDB Movie Reviews

## 🎯 Overview
A Machine Learning model that analyzes IMDB movie reviews and predicts
whether the sentiment is **Positive or Negative** using NLP techniques.

## 🏆 Results
| Dataset | Accuracy |
|---------|----------|
| Testing | 85.88% |

## 🔄 Project Pipeline
1. Data Loading – IMDB Movie Reviews dataset (50,000 reviews)
2. Text Preprocessing – Tokenization, Stopword removal, Lemmatization
3. Word Cloud Visualization
4. Feature Extraction – CountVectorizer (Bag of Words)
5. Model Training – Multinomial Naive Bayes
6. Evaluation – Accuracy Score & Classification Report
7. Real-time Prediction Test

## 🛠️ Technologies Used
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/ScikitLearn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-009688?style=for-the-badge&logo=python&logoColor=white)

## 📦 Libraries
- NLTK (Tokenization, Lemmatization, Stopwords)
- Scikit-learn (CountVectorizer, Naive Bayes)
- NumPy, Pandas
- Matplotlib, WordCloud

## 🧠 Model
- **Algorithm:** Multinomial Naive Bayes
- **Feature Extraction:** Bag of Words (CountVectorizer)
- **Train/Test Split:** 80% / 20%

## 📊 Classification Report
| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| Negative | 0.85 | 0.87 | 0.86 |
| Positive | 0.87 | 0.84 | 0.86 |

## 📁 Dataset
This project uses the IMDB Movie Reviews Dataset.
👉 [Download Here](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

After downloading, place this file in the project folder:
- | 🎬 [sentiment-analysis-imdb-nlp](https://github.com/mahak-maurya/sentiment-analysis-imdb-nlp) | IMDB Movie Sentiment Analysis — 85.88% Accuracy | NLTK, Scikit-learn, NLP |
