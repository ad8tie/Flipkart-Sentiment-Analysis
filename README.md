# 🛒 Customer Sentiment Analysis on Flipkart Product Reviews

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--learn-ML-orange?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/NLTK-NLP-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/VADER-Sentiment-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Platform-Google%20Colab-yellow?style=for-the-badge&logo=googlecolab"/>
</p>

<p align="center">
  <i>Classifying 2,296 Flipkart reviews using NLP & Machine Learning — with VADER comparison, mismatch detection, and topic modelling.</i>
</p>

---

## 📌 Overview

An end-to-end **NLP and Machine Learning** project that analyzes **2,296 real Flipkart customer reviews** to automatically classify sentiment as **Positive**, **Neutral**, or **Negative**.
This project goes beyond standard sentiment classification by implementing:
- ✅ A **dual-model approach** — ML + VADER lexicon comparison
- ✅ **Sentiment-rating mismatch detection** — unique business insight
- ✅ **LDA Topic Modelling** — identifies *why* customers are unhappy
- ✅ A **live sentiment predictor** — works on any new review instantly

---

## 📂 Dataset

| Property | Detail |
|---|---|
| Total Reviews | 2,296 |
| Columns | Product_name · Review · Rating |
| Rating Scale | 1 to 5 Stars |
| Missing Values | 8 (removed) |
| Class Split | 60% Positive · 6% Neutral · 34% Negative |

---

## 🛠️ Tech Stack

<p>
<img src="https://img.shields.io/badge/Python-blue?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/NLTK-green?style=flat-square"/>
<img src="https://img.shields.io/badge/Scikit--learn-orange?style=flat-square&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-blue?style=flat-square"/>
<img src="https://img.shields.io/badge/Seaborn-teal?style=flat-square"/>
<img src="https://img.shields.io/badge/VADER-purple?style=flat-square"/>
<img src="https://img.shields.io/badge/WordCloud-pink?style=flat-square"/>

---

## 🤖 Models & Results

| Model | Accuracy | F1 Score | Status |
|---|---|---|---|
| Logistic Regression | 88% | 90% | ✅ Good |
| Naive Bayes | 84% | 77% | ⚠️ Moderate |
| **Random Forest** | **90%** | **90%** | 🏆 Best |
> 🏆 **Random Forest** selected as the final model with `class_weight='balanced'` to handle class imbalance.

---

## 🔍 Key Insights

-  **Random Forest outperformed all models** with 90% accuracy and 90% F1 Score, making it the clear best model for this classification task.

-  **VADER and ML agreed 86.5% of the time** — when two completely different approaches reach the same conclusion, it strongly validates the model's predictions.

-  **93 reviews had mismatched sentiment** — customers who wrote positive text but rated 1-2 stars, or negative text but rated 4-5 stars. This reveals sarcasm, confusion, or genuine mixed experiences that a simple rating system misses.

-  **Camera quality, battery life, and delivery are the top complaints** — discovered through LDA Topic Modelling on negative reviews, going beyond just knowing customers are unhappy to understanding exactly why.

-  **Unhappy customers write more** — negative reviews are significantly longer than positive ones, suggesting dissatisfied customers feel the need to explain their experience in detail.

-  **Class imbalance was a real challenge** — 60% of reviews were 5-star, meaning without balancing, the model would simply predict positive every time. This was handled using `class_weight='balanced'` across all models.

---

## 📁 Repository Structure

    📁 Flipkart-Sentiment-Analysis
    ├── 📁 data/
    │    └── flipkart.xlsx
    ├── 📁 outputs/
    │    └── 8 visualisation graphs
    ├── majorproject.ipynb
    ├── requirements.txt
    └── README.md
