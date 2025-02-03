README.txt



GitHub README Structure
COVID-19 Vaccine Public Perception – Sentiment Analysis of Twitter Text
Overview
This project analyzes public sentiment toward COVID-19 vaccines using Twitter data. The goal is to understand trends, public concerns, and the overall perception of vaccines through Natural Language Processing (NLP) and machine learning.

Dataset & Data Collection
Source: Twitter API (via Tweepy)
Collected: Tweets containing COVID-19 vaccine-related keywords and hashtags
Data Processing: Text cleaning, removal of stop words, stemming, lemmatization
Features Extracted: User metadata, tweet engagement (likes, retweets), sentiment
Objective
To classify tweets into positive, negative, or neutral sentiment categories using NLP techniques and machine learning models, and gain insights into vaccine hesitancy and misinformation.

Technologies Used
Python Libraries: Pandas, NumPy, NLTK, Matplotlib, Seaborn, Scikit-Learn, TensorFlow/Keras
NLP Techniques: Tokenization, stopword removal, lemmatization, feature extraction
Machine Learning Models: Logistic Regression, Support Vector Machines (SVM), LSTM Neural Networks
Methodology
Data Collection: Gathered vaccine-related tweets via Twitter API
Data Preprocessing: Removed URLs, hashtags, special characters, and stopwords
Sentiment Analysis Approaches:
VADER (Lexicon-Based Approach)
Machine Learning (Logistic Regression, SVM, LSTM Model)
Visualization: Created heatmaps, bar charts, and word clouds to analyze trends
Performance Evaluation: Used accuracy, precision, recall, F1-score, and ROC AUC
Results & Insights
Sentiment Distribution:
Positive Tweets: 74,154
Neutral Tweets: 75,490
Negative Tweets: 29,464
Key Findings:
Positive sentiment increased over time as more vaccines were distributed.
Misinformation and vaccine hesitancy were dominant themes in negative sentiment tweets.
Keywords like "PfizerBioNTech" and "vaccine safety" were commonly discussed.
Files in Repository
twitter_sent-covid.ipynb – Jupyter Notebook with full analysis
Covid 19 Report.pdf – Summary report of findings
data/covid19_tweets.csv – Collected dataset (if shareable)





