# SpotTheScam
Spot the Scam – AI-Powered Job Scam Detector
Spot the Scam is an intelligent web application designed to detect potentially fraudulent job postings using machine learning and natural language processing (NLP). This project simulates real-world job listings and identifies scams with high accuracy using a Logistic Regression classifier trained on TF-IDF features. This machine learning-based web app built with Flask allows users to upload job listings in CSV format and predicts whether each job is likely genuine (0) or a scam (1) based on the job title and description.

# 🕵️‍♂️ Spot the Scam – Job Scam Detection Using Machine Learning

**Spot the Scam** is a Streamlit-powered web application designed to detect fraudulent job postings using natural language processing (NLP) and machine learning. It simulates real-world job listings using the Faker library, preprocesses the data, trains a logistic regression model, and allows users to upload their own job datasets (CSV format) to predict potential scams.

---

## 🚀 Features

- 🔍 AI Model Training: Simulates genuine and scam job posts and trains a logistic regression model using TF-IDF vectorization.
- 📁 CSV Upload: Upload job descriptions with `title` and `description` fields and predict whether each job is likely a scam.
- 📊 Visual Analysis:
  - Histogram of fraud probabilities
  - Pie chart of prediction outcomes
  - Table of top 10 suspicious listings
- 📈 Performance Metric: Displays the model’s F1 score to measure its effectiveness.

---

## 🧠 Technologies Used

- Python (pandas, numpy, re, sklearn, nltk, faker)
- Streamlit (for frontend UI)
- Matplotlib & Seaborn (for plotting)
- Scikit-learn (for ML model)
- NLTK (for stopword filtering)
- Faker (to simulate job data)

---

## 🗂️ Project Structure

```
spot-the-scam/
├── app.py              # Main Streamlit app
├── requirements.txt    # Dependencies
├── .gitignore          # Files to ignore in Git
└── README.md           # Project documentation
```

---

## 📄 Input Format

The uploaded CSV file must have at least two columns: `title` and `description`.

Example:

```csv
title,description
"Software Engineer","Join our remote team. Easy money. No experience needed."
"Data Analyst","We are looking for an experienced analyst with SQL skills."
```

---

## 💻 Run Locally

1. Clone the repository:
```bash
git clone https://github.com/Sbiswas765/spot-the-scam.git
cd spot-the-scam
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:
```bash
streamlit run app.py
```

---

## 📊 Output Example

- 📈 F1 Score of the trained model
- 📋 Table of uploaded jobs with fraud probabilities and predictions
- 📊 Histogram of fraud probability distribution
- 🥧 Pie chart summarizing scam vs genuine predictions
- 🚨 List of top 10 jobs with highest fraud probability

