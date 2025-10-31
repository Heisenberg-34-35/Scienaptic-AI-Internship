# Scienaptic AI_Internship

# 📊 **Financial News Sentiment Analyzer — Scienaptic AI Internship Project**

This project analyzes daily financial news headlines to predict DJIA (Dow Jones Industrial Average) stock market movements, built during an internship at **Scienaptic AI**.
It combines NLP techniques, sentiment analysis, and machine learning models to enable near real‑time risk assessment for investment teams.

---

## 📂 **Project Structure**

| File / Folder                             | Description                                                              |
| ----------------------------------------- | ------------------------------------------------------------------------ |
| `Combined_News_DJIA.csv`                  | Dataset with top 25 daily financial news headlines and DJIA labels (1/0) |
| `upload_DJIA_table.csv`                   | Historical DJIA stock data (Open, High, Low, Close, Volume)              |
| `RedditNews.csv`                          | Additional news dataset (optional / exploratory)                         |
| `Scieanptic_AI-1.ipynb`                   | Main analysis and EDA notebook                                           |
| `Scieanptic_AI-2.ipynb`                   | Advanced NLP, sentiment models & prediction                              |
| `Scienaptic_AI_Internship_Report.pdf`     | Final internship report                                                  |

---

## ⚙ **Tech Stack & Libraries**

Python (v3.11), Pandas, NumPy, Scikit-learn, NLTK, spaCy, TextBlob, VADER Sentiment, Transformers, Sentence-Transformers, XGBoost, Matplotlib, Seaborn

---

## 🚀 **Key Components**

* **Data preprocessing:** Merge headlines with stock data; clean and combine text.
* **Exploratory analysis:** Label distribution, word clouds, N‑grams, TF‑IDF.
* **Sentiment analysis:** VADER, TextBlob, FinBERT (finance‑specific BERT model).
* **NER & topic modeling:** Extract key entities and latent topics from headlines.
* **Machine learning models:** Logistic Regression, Random Forest, SVM, XGBoost.
* **Advanced NLP:** Sentence embeddings & clustering (t‑SNE, KMeans).
* **Real‑time prediction pipeline:** Predict daily DJIA movement & risk score from new headlines.

---

## ✅ **Outcome**

An end‑to‑end NLP & ML pipeline that transforms unstructured news into actionable market sentiment insights — supporting Scienaptic AI's teams with faster, data‑driven decision making.

---


