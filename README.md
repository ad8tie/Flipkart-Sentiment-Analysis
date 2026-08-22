# 🛒 Customer Sentiment Analysis on Flipkart Product Reviews

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikit-learn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-NLP-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow?logo=googlecolab)

---

## 📌 Overview
An end-to-end **NLP and Machine Learning** project that analyzes **2,296 real Flipkart customer reviews** to automatically classify sentiment as **Positive**, **Neutral**, or **Negative** — with deeper insights through VADER comparison, mismatch detection, and LDA topic modelling.

---

## 📂 Dataset
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
- ⚠️ **93 mismatched reviews** detected — written text contradicted the star rating
- 🔴 LDA Topic Modelling revealed top complaints — **camera quality, battery life, delivery**
- 📏 Negative reviews are **significantly longer** than positive ones

---

## 📈 Visualisations

### Rating Distribution
![Rating Distribution](outputs/graph1_ratings.png)

### Review Word Count
![Word Count](outputs/graph2_wordcount.png)

### Word Cloud — Customer Language
![Word Cloud](outputs/graph3_wordcloud.png)

### Confusion Matrix
![Confusion Matrix](outputs/graph4_confusionmatrix.png)

### Model Comparison
![Model Comparison](outputs/graph5_models.png)

### VADER vs ML Comparison
![VADER](outputs/graph6_vader.png)

### Mismatch Analysis
![Mismatch](outputs/graph7_mismatch.png)

### LDA Topic Modelling
![LDA](outputs/graph8_lda.png)

---

## 🔄 Project Workflow
## 🔄 Project Workflow
` ` `
Data Loading → EDA → Text Preprocessing → Sentiment Labelling
→ TF-IDF Vectorization → Model Training → Evaluation
→ VADER Comparison → Mismatch Detection → LDA Topic Modelling
→ Live Predictor
` ` `


---

## 🚀 How to Run
1. Open `majorproject.ipynb` in Google Colab
2. Click **Runtime → Run All**
3. Dataset loads automatically — no uploads needed

---

👤 **Author:** Aditi Singh  
🎓 *Data Science Capstone Project · LaunchED Global Internship · May 2026*
