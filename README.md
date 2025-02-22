# Sentiment Analysis of Tweets from Different Accounts and Linear Discriminant Analysis

## Overview
This project involves two key analyses:
1. **Sentiment Analysis of Tweets** – Analyzing tweets from different accounts to determine their sentiment (positive, negative, or neutral).
2. **Linear Discriminant Analysis (LDA)** – Performing LDA to reduce dimensionality and enhance classification performance in a dataset.

## Features
- Collect tweets from multiple accounts using Twitter API
- Preprocess text data (cleaning, tokenization, and vectorization)
- Perform sentiment analysis using NLP techniques
- Apply Linear Discriminant Analysis (LDA) for classification and dimensionality reduction
- Visualize results using data plots

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook (optional for exploration)
- Tweepy (for Twitter API access)
- Scikit-learn (for machine learning models)
- NLTK (for natural language processing)
- Pandas & NumPy (for data manipulation)
- Matplotlib & Seaborn (for visualization)

## Data Collection
- Fetch tweets using Tweepy
- Store collected data in a CSV file for further processing

## Sentiment Analysis
1. **Preprocessing**: Removing stopwords, punctuation, and tokenizing text.
2. **Feature Extraction**: Converting text to numerical vectors using TF-IDF.
3. **Classification**: Using machine learning models (e.g., Naïve Bayes, Logistic Regression) to predict sentiment.

## Linear Discriminant Analysis (LDA)
- Apply LDA on the dataset to reduce dimensions and improve classification accuracy.
- Visualize LDA results using scatter plots.

## Results
- Sentiment distribution of tweets
- Performance of different ML models in sentiment classification
- Impact of LDA on classification performance

## Future Improvements
- Improve sentiment classification with deep learning (e.g., LSTMs, Transformers)
- Expand dataset with more tweets and accounts
- Experiment with additional feature engineering techniques

## Author
Archana | [LinkedIn](https://www.linkedin.com/in/archana-senthil)

## License
This project is open-source and available under the [MIT License](LICENSE).


