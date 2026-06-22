#  Email / SMS Spam Classifier

A Machine Learning web application that classifies SMS and email messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) and a Multinomial Naive Bayes classifier.

##  Live Demo

https://email-spam-classifier-zixy.streamlit.app/

##  Features

* Spam and Not Spam classification
* Text preprocessing using NLTK
* TF-IDF Vectorization
* Multinomial Naive Bayes Model
* Interactive Streamlit interface

## 🛠️ Tech Stack

* Python
* Streamlit
* Scikit-learn
* NLTK
* Pandas
* NumPy

##  Project Structure

```text
Email-spam-classifier/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
├── README.md
│
└── notebooks/
    └── spam_classifier.ipynb
```

##  Notebook

The complete workflow including:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Text Preprocessing
* Feature Engineering
* Model Training
* Model Evaluation

is available in:

```text
notebooks/spam_classifier.ipynb
```

##  Run Locally

```bash
git clone https://github.com/zixywho/Email-spam-classifier.git
cd Email-spam-classifier
pip install -r requirements.txt
streamlit run app.py
```

##  Author

GitHub: https://github.com/zixywho
