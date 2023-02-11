# Sentiment-analysis
Gathered Tweets related to Stock Market Crash in 2022 from twitter on #stockmarketcrash.
The sentiment of the tweets column consists of three categories :
Positive 12542 tweets
Neutral 11498 tweets
Negative 9906 tweets

# Libraries used for this project:
1) train_test_split from sklearn for training and testing the data 
2) Countvectorizer from sklearn.feature_extraction for converting the text docs to a matrix of token counts which can be used as an input variable for machine learning algorithm.
3) MultinomialNB from sklearn.naives_bayes for implementing multinomial naives bayes algo for text classification
4) metrics for measuring accuracy
