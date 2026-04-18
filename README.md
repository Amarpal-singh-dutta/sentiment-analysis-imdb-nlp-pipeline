# 🎬 IMDB Sentiment Analysis using NLP

## 📌 Project Overview

This project builds a sentiment analysis system to classify movie reviews as **positive or negative** using Natural Language Processing (NLP) techniques.

Multiple text representation methods and machine learning models are compared to identify the best performing approach.

---

## 🚀 Features

* Text preprocessing (HTML removal, cleaning, normalization)
* Feature engineering using:

  * Bag of Words (BoW)
  * TF-IDF
  * Word2Vec
* Model comparison:

  * Logistic Regression
  * Naive Bayes
* Evaluation using:

  * Accuracy
  * Precision, Recall, F1-score
  * Confusion Matrix
* Custom prediction on new reviews

---

## 🧠 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Gensim (Word2Vec)
* Matplotlib, Seaborn

---

## 📂 Dataset

Dataset used: IMDB Movie Reviews Dataset
(50,000 labeled reviews)

---

## ⚙️ Workflow

1. **Data Cleaning**

   * Removed HTML tags
   * Lowercased text
   * Removed special characters

2. **Feature Engineering**

   * BoW: frequency-based representation
   * TF-IDF: importance-based representation
   * Word2Vec: semantic vector representation

3. **Model Training**

   * Logistic Regression
   * Naive Bayes

4. **Evaluation**

   * Compared models using accuracy and F1-score
   * Generated confusion matrix

---

## 📊 Results

| Model                          | Accuracy        |
| ------------------------------ | --------------- |
| TF-IDF + Logistic Regression   | **~87% (Best)** |
| BoW + Logistic Regression      | ~86%            |
| Word2Vec + Logistic Regression | ~81%            |

👉 TF-IDF performed best due to its ability to capture word importance.

---

## 🔮 Example Prediction

Input:
"This movie was absolutely amazing!"

Output:
**Positive**

---



## 📌 Future Improvements

* Use deep learning models (LSTM, BERT)
* Hyperparameter tuning
* Deploy using Streamlit

---

## 👤 Author

Amarpal Singh Dutta
(Machine Learning & Data Science Enthusiast)
