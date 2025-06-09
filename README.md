# 🛡️ SpamShield: Email Spam Detection System Using Naive Bayes

A lightweight and efficient machine learning model to classify email messages as **Spam** or **Not Spam** using the **Multinomial Naive Bayes** algorithm. Built for fast deployment, interpretability, and real-time classification.

---

## 📌 Project Overview

Email spam poses significant challenges in communication systems. This project presents a practical implementation of a **spam detection engine** leveraging text classification techniques and probabilistic modeling. It includes:

- 🧹 Data preprocessing and vectorization (Bag of Words)
- 🧠 Model training using Naive Bayes
- 📈 Evaluation and performance metrics
- 🌐 Web application via Streamlit for user interaction

---

## 🚀 Features

- 🔍 Real-time email classification
- ⚡ Fast training and inference with Naive Bayes
- 🧠 Text preprocessing using CountVectorizer
- 📊 Evaluation using confusion matrix and F1-score
- 🖥️ Interactive UI built with Streamlit

---

## 📁 Project Structure

spamshield-email-spam-classifier/
│
├── 📁 data/ # Data source or reference
├── 📁 notebooks/ # Jupyter analysis & EDA
├── 📁 models/
│ ├── 📄 spam_model.pkl # Trained model
│ └── 📄 vectorizer.pkl # CountVectorizer instance
├── 📄 streamlit_app.py # Main Streamlit application
├── 📄 train_model.py # Model training script
├── 📄 requirements.txt # Python dependencies
└── 📄 README.md # Project documentation

---

## 🧪 Tech Stack

- 🐍 Python 3.8+
- 🧮 Scikit-learn
- 📊 Pandas, NumPy
- 🌐 Streamlit
- 💾 Joblib

---

## 📊 Model Performance

| 📐 Metric     | 🔢 Value    |
|---------------|-------------|
| ✅ Accuracy   | 98.5%       |
| 🎯 Precision  | 98.9%       |
| 📥 Recall     | 97.6%       |
| 📊 F1-Score   | 98.2%       |

> Evaluated on the SMS Spam Collection dataset from UCI.

---

## 🛠️ Setup Instructions

### 1. 🧾 Clone the Repository
git clone project repository
cd spamshield-email-spam-classifier
2. 📦 Install Dependencies
pip install -r requirements.txt
3. 🏗️ Train the Model (if not using pre-trained)
python train_model.py

📦 Model Files
Ensure the following files are present or generated:

📄 spam_model.pkl — trained Naive Bayes model

📄 vectorizer.pkl — CountVectorizer object


📜 License
This project is licensed under the MIT License.
