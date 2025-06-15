# SpotTheScam
🕵️‍♂️ Spot the Scam – AI-Powered Job Scam Detector
Spot the Scam is an intelligent web application designed to detect potentially fraudulent job postings using machine learning and natural language processing (NLP). This project simulates real-world job listings and identifies scams with high accuracy using a Logistic Regression classifier trained on TF-IDF features.This is a machine learning-based web app built with Flask that allows users to upload job listings in CSV format and predicts whether each job is likely genuine (0) or a scam (1) based on the job title and description.

🚀 Key Features
🧠 AI-Powered Detection: Automatically flags scam job listings based on title and description.

📁 CSV Upload Support: Upload your job posting dataset for batch prediction.

📊 Visual Insights:

Histogram of fraud probabilities.

Pie chart summary of scam vs genuine predictions.

Top 10 most suspicious listings ranked by fraud probability.

📈 Model Evaluation: Real-time display of F1 score to track model performance.

⚡ Fast & Interactive: Built using Streamlit for a responsive and interactive user experience.

🧠 Tech Stack
Category	Tools Used
💻 Frontend	Streamlit
🔎 NLP	NLTK, Regex, Scikit-learn TF-IDF
🤖 Machine Learning	Logistic Regression
📊 Visualization	Matplotlib, Seaborn
🧪 Testing Data	Faker (to generate synthetic job listings)
📦 Dependency Mgt.	pip + requirements.txt

🗂️ Project Structure
bash
Copy
Edit
📁 spot-the-scam/
│
├── app.py                # Streamlit app
├── .gitignore            # Git ignore config
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
📄 Sample Input Format
Upload a .csv file with two columns:

csv
Copy
Edit
title,description
"Software Engineer","Join a dynamic team. No experience needed. Quick cash!"
"Data Analyst","We need an experienced analyst with knowledge in SQL and Python."
