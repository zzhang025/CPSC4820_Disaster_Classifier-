# CPSC4820_Disaster_Classifier-

## Project – Real or Not? NLP with Disaster Tweets
This is a data science competition belonging to Kaggle Machine Learning Challenge.

https://www.kaggle.com/c/nlp-getting-started/overview

The data at hand is a collection of tweets that are related to disasters or accidents. There are five columns: Id, keyword, location, text, and target. The Id is the unique identifier for the tweets, and the text column contains the tweet. The keyword contains a particular word from the tweet, with the location of the tweet in the location column. The target column contains a binary value of 0 or 1, with 0 being the tweet classified as not related to a disaster and 1 being the tweet is about an actual fatal incident.

We used matplotlib and seaborn for visualizations, along with other packages like nltk and sklearn. We broke down the tweets into a list of words splitting them by space and removed the stop words like: the, and, you, it, et cetera. We also changed the words to their base form to avoid having multiple words with the same meaning in our dataset. We further used Logistic Regression to classify the words that relate to disaster and visualize the parameters of a model using word cloud.
