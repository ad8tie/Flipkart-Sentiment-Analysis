# Customer Sentiment Analysis on Flipkart Product Reviews

## Overview
An end-to-end NLP and Machine Learning project that analyzes 2,296 real Flipkart customer reviews to automatically classify sentiment as Positive, Neutral, or Negative — with deeper insights through VADER comparison, mismatch detection, and LDA topic modelling.

## Dataset
- 2,296 Flipkart product reviews
- Columns: Product_name, Review, Rating (1–5 stars)

## Tech Stack
Python · Pandas · NumPy · NLTK · Scikit-learn · VADER · Matplotlib · Seaborn · WordCloud · Google Colab

## Models & Results
| Model | Accuracy | F1 Score |
|---|---|---|
| Logistic Regression | 88% | 90% |
| Naive Bayes | 84% | 77% |
| Random Forest ✅ | 90% | 90% |

## Key Insights
- 90% accuracy achieved using Random Forest
- 86.5% agreement between ML model and VADER lexicon
- 93 mismatched reviews detected where written text contradicted the star rating
- LDA Topic Modelling revealed top complaints — camera quality, battery life, and delivery
- Negative reviews found to be significantly longer than positive ones

## Project Workflow
Data Loading → EDA → Text
