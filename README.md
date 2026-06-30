# NLP Sentiment Analysis

## Project Overview

This project performs Sentiment Analysis on movie reviews using Natural Language Processing (NLP) and Machine Learning.

The text data is cleaned and preprocessed before converting it into numerical features using TF-IDF. A Logistic Regression model is then trained to classify reviews as **Positive** or **Negative**.

---

## Features

- Text Cleaning
- Tokenization
- Stopword Removal
- Stemming
- Lemmatization
- TF-IDF Vectorization
- Word Frequency Analysis
- Logistic Regression Classifier
- Model Evaluation
- ROC Curve
- Confusion Matrix
- Word Cloud Visualization
- Predict Sentiment for New Reviews
- Save and Load Trained Model

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- WordCloud
- Joblib
- Jupyter Notebook

---

## Project Files

```
NLP_Sentiment_Analysis.ipynb
README.md
requirements.txt
top_words_by_sentiment.png
sentiment_confusion_matrix.png
roc_curve.png
positive_wordcloud.png
negative_wordcloud.png
sentiment_model.pkl
```

---

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pandas numpy nltk scikit-learn matplotlib seaborn wordcloud joblib
```

---

## Dataset

This project uses the IMDB Movie Reviews dataset for sentiment classification.

---

## Results

The trained Logistic Regression model predicts whether a movie review is **Positive** or **Negative** after preprocessing the text using NLP techniques.

The project also generates visualizations such as:

- Word Frequency Charts
- Word Clouds
- Confusion Matrix
- ROC Curve

---

## Author

**Saibul Islam**

GitHub: https://github.com/saibulislam
