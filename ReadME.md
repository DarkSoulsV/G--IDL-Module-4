# NLP Disaster Tweets Project

This is my project for the Kaggle competition **“Natural Language Processing with Disaster Tweets”**, completed as part of Module 4 (sequence models) in the Deep Learning course.

The goal is to classify tweets as either:
- **1 — disaster**
- **0 — not disaster**

---

## What’s inside

- A Jupyter Notebook with:
  - short problem and dataset overview
  - EDA (class balance, missing values, tweet length, etc.)
  - text cleaning and preprocessing
  - TF-IDF + Logistic Regression baseline
  - LSTM model with embeddings
  - results and comparison between both models
  - conclusion + Kaggle submission file

- `submission.csv` — the final file I uploaded to Kaggle.

---

## Model Results

- **TF-IDF + Logistic Regression:** 0.8056 validation accuracy  
- **LSTM model:** ~0.79 validation accuracy  
- Final Kaggle score: **0.77597**

The baseline performed slightly better, which is normal for small datasets with short text like tweets.

---

## How to run

You can open the notebook and run all cells in order.  
The only required libraries are:
- pandas  
- numpy  
- scikit-learn  
- tensorflow / keras  
- matplotlib, seaborn  

---
