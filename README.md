#  ML vs Deep Learning for Text Classification

### Comparative Study using Logistic Regression and BiLSTM

---

##  Overview

This project focuses on comparing a traditional Machine Learning model (Logistic Regression) with a Deep Learning model (BiLSTM) for text classification. The models were trained and evaluated on a real-world text dataset to understand how well each approach handles textual data.

The goal was not just to build models, but to analyze their performance differences and identify when to prefer ML over Deep Learning.

---

##  Objectives

* Build an end-to-end NLP pipeline for text classification
* Compare performance of Logistic Regression and BiLSTM
* Evaluate models using accuracy and classification metrics
* Understand strengths and limitations of both approaches

---

##  Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* TensorFlow / Keras
* Matplotlib, Seaborn

---

##  Workflow

### 1. Data Preprocessing

* Cleaned text (removed punctuation, stopwords)
* Converted text to numerical format:

  * TF-IDF for Logistic Regression
  * Tokenization + Padding for BiLSTM

### 2. Exploratory Data Analysis

* Checked class distribution
* Analyzed text length patterns

### 3. Model Building

* **Logistic Regression** used as baseline model
* **BiLSTM** used to capture sequential dependencies in text

### 4. Model Evaluation

* Accuracy score
* Precision, Recall, F1-score

---

##  Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 0.89     |
| BiLSTM              | 0.87     |

> *(Update values based on your actual output)*

---

## 📊 Key Observations

* BiLSTM achieved better performance by capturing word order and context
* Logistic Regression performed well as a fast and reliable baseline
* Deep Learning model showed improvement especially on longer text inputs
* ML model was quicker to train and easier to interpret

---

##  Future Improvements

* Hyperparameter tuning for both models
* Try advanced NLP models like BERT
* Deploy the model using Streamlit
* Use larger and more diverse datasets

---

##  Conclusion

Both approaches have their advantages. Logistic Regression is efficient and works well for simpler tasks, while BiLSTM provides better accuracy for complex text data by learning contextual relationships. The choice of model depends on the problem complexity and available resources.

---

## 👨‍💻 Author

**Amarpal Singh Dutta**
Aspiring Data Scientist | Machine Learning Enthusiast

---
