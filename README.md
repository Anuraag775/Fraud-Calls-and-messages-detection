# 📵 Fraud Calls and Messages Detection Using Machine Learning

This project aims to detect fraudulent calls and messages using machine learning techniques. By leveraging Naive Bayes classification and natural language processing, it enhances detection accuracy and minimizes false positives and negatives.

## 🎯 Objective

Develop and evaluate a real-time fraud detection system that classifies SMS and call messages as legitimate or fraudulent using Naive Bayes and compares performance against K-Nearest Neighbors (KNN).

## 🚀 Features

- Text preprocessing pipeline (cleaning, tokenization, stopword removal, stemming)
- Feature extraction using Count Vectorizer
- Implementation of Naive Bayes and KNN classifiers
- Performance metrics: Accuracy, Precision, Recall, F1 Score
- Interactive message input and fraud prediction UI

## 🧠 Algorithms Used

| Algorithm     | Accuracy | Precision | Recall | F1 Score |
|---------------|----------|-----------|--------|----------|
| KNN           | 94%      | 93%       | 45%    | 62%      |
| Naive Bayes   | 98%      | 87%       | 92%    | 90%      |

## 🗂️ Dataset

- **Source**: SMS spam dataset (approx. 5,927 messages)
- **Classes**: Legitimate (label 0), Fraudulent (label 1)

## 🛠️ Tech Stack

- **Language**: Python 3.7.6
- **Libraries**: NumPy, Pandas, Scikit-learn, NLP Toolkit
- **IDE**: Jupyter Notebook

## ⚙️ Installation

```bash
git clone https://github.com/your-username/fraud-detection-ml.git
cd fraud-detection-ml
pip install -r requirements.txt
jupyter notebook
