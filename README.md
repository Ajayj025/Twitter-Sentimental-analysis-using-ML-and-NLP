# 🐦 Twitter Sentiment Analysis using Linear SVM

This project performs sentiment analysis on tweets using the [Sentiment140 dataset](https://www.kaggle.com/kazanova/sentiment140) and builds a classification model using Linear Support Vector Machine (SVM).

---

## 📌 Objective

- Classify tweets into **positive** (1) and **negative** (0) sentiment.
- Apply **text preprocessing**, **TF-IDF vectorization**, and **Linear SVM classification**.
- Evaluate model performance using **accuracy scores**.

---

## 📁 Dataset

- **Source**: [Sentiment140 on Kaggle](https://www.kaggle.com/kazanova/sentiment140)
- **Size**: 1.6 million tweets
- **Labels**:
  - `0` → Negative sentiment
  - `4` → Positive sentiment (converted to `1` in preprocessing)

---

## 🛠️ Technologies Used

- Python 🐍
- Scikit-learn 🤖
- NLTK for NLP tasks 📚
- TF-IDF Vectorizer
- Linear SVM Classifier

---

## ⚙️ Project Workflow

1. **Install dependencies**
2. **Load and clean the dataset**
3. **Preprocess text (lowercasing, stopwords removal, stemming)**
4. **Convert text to TF-IDF features**
5. **Split data into training/testing sets**
6. **Train Linear SVM model**
7. **Evaluate performance on both sets**

---

## 🧪 Model Accuracy

| Dataset     | Accuracy (%) |
|-------------|---------------|
| Training Set| 84.3%         |
| Testing Set | 82.7% ✅      |

---

## 📦 Installation

```bash
pip install numpy pandas scikit-learn nltk kaggle
