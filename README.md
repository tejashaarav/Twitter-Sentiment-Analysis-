# Twitter-Sentiment-Analysis--A-NLP-Use-Case-for-Beginners

Sentiment analysis is the process of recognizing and categorizing the sentiments represented in a text source. When analyzed, tweets may generate a large quantity of sentiment data. These statistics are important in understanding people's opinions on a range of subjects.

To calculate consumer perception, we must create an Automated Machine Learning Sentiment Analysis Model. It is challenging to apply models to them because of the existence of non-useful characters (together referred to as noise) alongside relevant data.

In this post, we will assess the sentiment of tweets from the Sentiment140 dataset using a machine learning pipeline that includes three classifiers (Logistic Regression, Bernoulli Naive Bayes, and SVM) as well as the Term Frequency-Inverse Document Frequency method (TF-IDF). The accuracy and F1 Scores of these classifiers are then used to evaluate their performance.


Problem Statement
In this project, we try to implement a Twitter sentiment analysis model that helps to overcome the challenges of identifying the sentiments of the tweets. The necessary details regarding the dataset are:

The dataset provided is the Sentiment140 Dataset which consists of 1,600,000 tweets that have been extracted using the Twitter API. The various columns present in the dataset are:

target: the polarity of the tweet (positive or negative)
ids: Unique id of the tweet
date: the date of the tweet
flag: It refers to the query. If no such query exists then it is NO QUERY.
user: It refers to the name of the user that tweeted
text: It refers to the text of the tweet
