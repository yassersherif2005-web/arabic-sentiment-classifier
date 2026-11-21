# Arabic Sentiment Classifier

A machine learning project that classifies Arabic tweets as **positive** or **negative** using natural language processing (NLP).

## Overview

- **Dataset:** Arabic Sentiment Twitter Corpus (arbml) - 47,000 training tweets and 11,751 test tweets
- **Preprocessing:** Arabic text cleaning (removing links, mentions, and non-Arabic characters)
- **Features:** TF-IDF with unigrams and bigrams (20,000 features)
- **Model:** Logistic Regression
- **Test accuracy:** 76.4%

## Approach

1. Loaded and explored the dataset (balanced classes: ~23.9k positive, ~23.1k negative)
2. Cleaned the Arabic text with regex-based preprocessing
3. Converted text to numerical features using TF-IDF
4. Trained a Logistic Regression baseline (75.8% accuracy)
5. Improved the model by adding bigram features (+0.6% accuracy)

## Tools

Python, scikit-learn, pandas, Hugging Face Datasets, Google Colab

## Try it

Open `arabic_sentiment_classifier_.ipynb` in Google Colab and run the cells. The final cell lets you test the model on any Arabic sentence.
