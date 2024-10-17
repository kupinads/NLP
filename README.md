# Tweet Sentiment Classifier

## Overview

This project analyzes the Tweet Sentiment Extraction dataset to build a sentiment classifier using the Bag-of-Words (BoW) technique and a DecisionTreeClassifier. The project involves text preprocessing with Python's `nltk` library, enabling effective sentiment analysis on tweets.

## Dataset Source
### Source - https://www.kaggle.com/competitions/tweet-sentiment-extraction/data?select=train.csv
### Description
Each row contains the text of a tweet and a sentiment label. In the training set you are provided with a word or phrase drawn from the tweet (selected_text) that encapsulates the provided sentiment.

## Objectives

- Analyze the Tweet Sentiment Extraction dataset.
- Transform text data using the Bag-of-Words method.
- Build a sentiment classifier to categorize tweets as positive, negative, or neutral.

## Steps Involved

1. **Data Analysis**: Explore the dataset to understand the distribution of sentiments.
2. **Text Preprocessing**: Utilize `nltk` for tokenization, stop-word removal, and text normalization.
3. **Vectorization**: Apply the Bag-of-Words model to convert text into numerical features.
4. **Model Building**: Train a Decision Tree classifier on the vectorized data and evaluate its performance.

## Requirements

- Python 3.10.12
- `nltk`
- `scikit-learn`
- `pandas`
