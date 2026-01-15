 Spam Message Detection System

A Machine Learning–based **Spam Message Detection System** that classifies messages as **Spam** or **Not Spam (Ham)**.  
This project demonstrates text preprocessing, feature extraction, and classification using Python and scikit-learn.

## 📌 Project Overview

Spam detection is a common real-world NLP problem.  
This project uses **Natural Language Processing (NLP)** techniques and a trained machine learning model to identify spam messages effectively.

---

🚀 Features
- Classifies messages as **Spam** or **Ham**
- Text preprocessing (cleaning & tokenization)
- Feature extraction using vectorization
- Pre-trained ML model for fast predictions
- Simple and lightweight implementation


 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries Used:**
  - NumPy
  - Pandas
  - Scikit-learn
  - NLTK
  - Streamlit (optional UI)

---

## 📂 Dataset

- SMS Spam Collection Dataset  
- Contains labeled messages: `spam` and `ham`

⚙️ How It Works

1. Load the dataset and clean the text
2. Convert text into numerical features using a vectorizer
3. Train a classification model
4. Save the trained model and vectorizer
5. Use the model to predict whether a message is spam or not

🧠 Machine Learning Model

- Text Vectorization: **CountVectorizer / TF-IDF**
- Classification Algorithm: **Naive Bayes / Logistic Regression**
- Evaluation based on accuracy and precision
 🧪 Example

```text
Input Message:
"Congratulations! You have won a free prize."

Prediction:
Spam
