# 🛒 Customer Sentiment Analysis on Flipkart Product Reviews

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikit-learn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-NLP-green?logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow?logo=googlecolab)

---

## 📌 Overview
An end-to-end **NLP and Machine Learning** project analyzing **2,296 real Flipkart customer reviews** to automatically classify sentiment as **Positive**, **Neutral**, or **Negative** — with deeper insights through VADER comparison, mismatch detection, and LDA topic modelling.

---

## 📊 Dataset
| Property | Detail |
|---|---|
| Total Reviews | 2,296 |
| Columns | Product_name · Review · Rating |
| Rating Scale | 1 to 5 Stars |
| Missing Values | 8 (removed) |

---

## 🛠️ Tech Stack
`Python` `Pandas` `NumPy` `NLTK` `Scikit-learn` `VADER` `Matplotlib` `Seaborn` `WordCloud` `Google Colab`

---

## 🤖 Models & Results
| Model | Accuracy | F1 Score |
|---|---|---|
| Logistic Regression | 88% | 90% |
| Naive Bayes | 84% | 77% |
| **Random Forest** ✅ | **90%** | **90%** |

---

## 🔍 Key Insights
- 🎯 **90% accuracy** achieved using Random Forest
- 🤖 **86.5% agreement** between ML model and VADER lexicon
- ⚠️ **93 mismatched reviews** detected — text contradicted the star rating
- 🔴 **Top complaints** — camera quality, battery life, delivery issues
- 📏 Negative reviews are **significantly longer** than positive ones

---

## 🔄 Project Workflow
