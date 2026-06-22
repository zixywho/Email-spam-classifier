# Email / SMS Spam Classifier

A Machine Learning web application that classifies messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) techniques and a Multinomial Naive Bayes model.

## Live Demo

**Application:** https://email-spam-classifier-zixy.streamlit.app/

---

## Overview

This project uses Natural Language Processing (NLP) to analyze the content of an email or SMS message and determine whether it is spam.

The application performs text preprocessing, converts the text into numerical features using TF-IDF Vectorization, and then predicts the category using a trained Multinomial Naive Bayes classifier.

---

## Features

* Classifies messages as Spam or Not Spam
* Text preprocessing using NLTK
* TF-IDF Vectorization
* Multinomial Naive Bayes Classification
* Interactive web interface using Streamlit
* Deployed on Streamlit Cloud

---

##  Tech Stack

### Programming Language

* Python

### Libraries & Frameworks

* Streamlit
* Scikit-learn
* NLTK
* NumPy
* Pandas
* Pickle

### Machine Learning

* TF-IDF Vectorizer
* Multinomial Naive Bayes

---

##  Project Structure

```text
Email-spam-classifier/
│
├── app.py               # Streamlit application
├── model.pkl            # Trained ML model
├── vectorizer.pkl       # Trained TF-IDF vectorizer
├── requirements.txt     # Project dependencies
├── .gitignore
└── README.md
```

---

##  How It Works

### 1. Text Preprocessing

The input message undergoes the following preprocessing steps:

* Convert text to lowercase
* Tokenization
* Remove punctuation
* Remove stopwords
* Stemming using Porter Stemmer

### 2. Feature Extraction

The processed text is converted into numerical vectors using:

```python
TfidfVectorizer
```

### 3. Prediction

The vectorized text is passed to a trained:

```python
MultinomialNB
```

model to classify the message as:

* Spam
* Not Spam

---

## ▶️ Running Locally

### Clone the Repository

```bash
git clone https://github.com/zixywho/Email-spam-classifier.git
cd Email-spam-classifier
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

---

## 📊 Machine Learning Pipeline

```text
Input Message
      │
      ▼
Text Preprocessing
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Multinomial Naive Bayes
      │
      ▼
Spam / Not Spam Prediction
```

---

## Future Improvements

* Support for multiple machine learning models
* Display prediction confidence score
* Email attachment analysis
* Deep Learning based spam detection
* Improved UI/UX
* Model performance dashboard

---

## Author

**Zixywho**

GitHub: https://github.com/zixywho

---

## 📜 License

This project is open-source and available under the MIT License.
