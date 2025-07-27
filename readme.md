# 🧠 Amazon Review Sentiment Analysis with NLP

This project analyzes sentiment in Amazon product reviews using both traditional NLP (VADER) and transformer-based models (RoBERTa). It explores how customer sentiment aligns with review scores and compares the effectiveness of two sentiment analysis approaches.

---

## 📌 Objective

- Understand sentiment trends in Amazon product reviews
- Compare rule-based (VADER) and deep learning-based (RoBERTa) sentiment predictions
- Visualize how sentiment correlates with star ratings

---

## 🗂️ Dataset

- Source: [Kaggle Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
- Subset used: 500 reviews for demonstration

---

## 🔧 Tools & Libraries

- Python, Pandas, NumPy
- NLTK (VADER, tokenization, lemmatization)
- Hugging Face Transformers (`cardiffnlp/twitter-roberta-base-sentiment`)
- PyTorch
- Seaborn, Matplotlib
- tqdm (for progress bar)

---

## 📊 Key Features

- Text preprocessing pipeline (lowercasing, stopword removal, lemmatization)
- VADER sentiment analysis with positive, neutral, and negative scores
- RoBERTa sentiment analysis using pretrained transformer model
- Comparison of sentiment vs. review scores
- Data visualizations (bar plots, sentiment distribution)

---

## 📉 Results

- VADER sentiment scores correlate well with star ratings.
- RoBERTa provides more nuanced sentiment predictions on short, informal reviews.
- Sentiment becomes increasingly positive as the star rating increases, as expected.

---

