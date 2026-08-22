# Flipkart-Sentiment-Analysis
📌 Overview

This project performs end-to-end Natural Language Processing (NLP) and Machine Learning on 2,296 real customer reviews scraped from Flipkart. The goal is to automatically classify each review as Positive, Neutral, or Negative — and extract deeper business insights beyond simple classification.
The project goes beyond a standard sentiment classifier by implementing a dual-model approach (ML + VADER), sentiment-rating mismatch detection, and LDA topic modelling to uncover the root causes of customer dissatisfaction.

🏗️ Project Architecture

Raw Data
   │
   ▼
Data Loading & EDA ──► Rating distribution · Word clouds · Review length analysis
   │
   ▼
Text Preprocessing ──► Lowercase · Remove punctuation · Stopwords · Lemmatization
   │
   ▼
Sentiment Labelling ──► Rating ≥ 4 → Positive · Rating = 3 → Neutral · Rating ≤ 2 → Negative
   │
   ▼
Feature Engineering ──► TF-IDF Vectorization (5,000 features)
   │
   ▼
Model Training ──► Logistic Regression · Naive Bayes · Random Forest
   │
   ▼
Evaluation ──► Accuracy · F1 Score · Confusion Matrix · Classification Report
   │
   ▼
Advanced Analysis ──► VADER · Mismatch Detection · LDA Topic Modelling
   │
   ▼
Live Predictor ──► Real-time sentiment prediction on any new review

🌟 Standout Features
1. Three ML models trained and compared side by side
2. Dual sentiment approach — ML + VADER lexicon
3. Mismatch detection — unique business intelligence insight
4. LDA topic modelling — identifies why customers are unhappy
5. Live sentiment predictor — works on any new review in real time
6. Class imbalance handled with class_weight='balanced'


🚀 How to Run
1.Click the Open in Colab badge at the top
2.Click Runtime → Run All
3.Dataset loads automatically — no file upload needed

