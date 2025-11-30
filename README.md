# Twitter Sentiment Analysis on US Airline Tweets

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)  
![Pandas](https://img.shields.io/badge/Pandas-2.2-green?logo=pandas&logoColor=white)  
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.5-orange?logo=scikitlearn&logoColor=white)  
![NLTK](https://img.shields.io/badge/NLTK-3.8-red?logo=nltk&logoColor=white)  
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue)

## Project Overview

This repository contains a Jupyter Notebook for sentiment analysis on tweets about US airlines. The analysis classifies tweets into positive, negative, or neutral sentiments using natural language processing (NLP) techniques and machine learning. Key steps include data cleaning, text preprocessing (tokenization, stop word removal, stemming), TF-IDF vectorization, and training a RandomForestClassifier. Evaluation includes accuracy, classification reports, and confusion matrices.

Dataset: 14,640 tweets from February 2015, sourced from Kaggle (link: [Twitter US Airline Sentiment](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)). Focuses on airlines like Virgin America, United, Southwest, Delta, US Airways, and American.

Key achievements:  
- Achieves high accuracy in sentiment classification.  
- Visualizes performance with confusion matrices.  

Current as of November 30, 2025.

## Repository Contents

- `Copy_of_TwitterSentimentAnalysisonUSAirlineTweets_Commented (1) (1).ipynb`: The main Jupyter Notebook with:  
  - Data loading from `Tweets.csv`.  
  - Text cleaning and preprocessing (lowercasing, removing punctuation/URLs, tokenization, stop words removal, stemming with PorterStemmer).  
  - Feature extraction using TF-IDF Vectorizer.  
  - Model training with RandomForestClassifier.  
  - Evaluation: Accuracy score, classification report, confusion matrix visualization.  

**Note**: The dataset (`Tweets.csv`) is not included;
