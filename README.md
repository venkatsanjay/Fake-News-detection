# 📰 Fake News Detection using Machine Learning

## 📌 Project Overview
This project focuses on detecting **fake news articles** using Machine Learning techniques.  
The system classifies news as **Real** or **Fake** based on the article's title and author content.

It demonstrates **end-to-end ML workflow** — from data preprocessing to model deployment.

---

## 🎯 Objectives
- Build a **text classification model** for fake news detection.
- Apply **Natural Language Processing (NLP)** techniques to clean and prepare text data.
- Train and evaluate a **Logistic Regression model**.
- Create a **predictive system** for new unseen data.

---

## 📂 Dataset
- **Source:** Kaggle Fake News Dataset *(train.csv)*
- **Features Used:**
  - `title`
  - `author`
  - `label` (0: Real, 1: Fake)

---

## ⚙️ Tech Stack
- **Language:** Python
- **Libraries & Tools:**
  - pandas, numpy
  - scikit-learn
  - NLTK
  - TF-IDF Vectorizer
  - Jupyter Notebook

---

## 🔄 Workflow
1. **Data Loading & Inspection**
2. **Data Preprocessing**
   - Merge `title` and `author` into a single column.
   - Remove non-alphabetical characters.
   - Convert text to lowercase.
   - Remove stopwords.
   - Apply stemming using **PorterStemmer**.
3. **Feature Extraction**
   - Convert text to numerical features using **TF-IDF Vectorization**.
4. **Model Training**
   - Logistic Regression model trained on 80% of the dataset.
5. **Model Evaluation**
   - Accuracy: **97.5% (Train)** / **96.3% (Test)**
6. **Prediction System**
   - Takes user input (news text) and predicts if it's *Real* or *Fake*.

---

## 📊 Results
| Metric        | Training Data | Test Data |
|---------------|--------------|-----------|
| Accuracy      | 97.5%        | 96.3%     |

---


