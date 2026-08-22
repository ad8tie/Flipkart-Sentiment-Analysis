# 🛒 Customer Sentiment Analysis — Flipkart Product Reviews

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ad8tie/Flipkart-Sentiment-Analysis/blob/main/majorproject.ipynb)
![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview
An end-to-end **NLP and Machine Learning** project that analyzes 2,296 real Flipkart customer reviews to automatically classify sentiment as **Positive**, **Neutral**, or **Negative**. The project goes beyond standard classification by implementing a dual-model approach, mismatch detection, and topic modelling to extract actionable business insights.

---

## 🤖 Models & Results

| Model | Accuracy | F1 Score |
|---|---|---|
| Logistic Regression | 88% | 90% |
| Naive Bayes | 84% | 77% |
| **Random Forest** ✅ | **90%** | **90%** |

---

## 🔍 Key Insights
- **86.5%** agreement between ML model and VADER lexicon analysis
- **93 mismatched reviews** detected where text contradicted the star rating
- **LDA Topic Modelling** revealed top complaints — camera quality, battery life, and delivery issues
- Negative reviews are significantly longer than positive ones

---

## 🛠️ Tech Stack
`Python` `Pandas` `NLTK` `Scikit-learn` `VADER` `Matplotlib` `Seaborn` `WordCloud` `Google Colab`

---

## 🚀 How to Run
Click **Open in Colab** → **Runtime → Run All**
> Dataset loads automatically from Google Drive. No file uploads needed.

---

## 📁 Structure
