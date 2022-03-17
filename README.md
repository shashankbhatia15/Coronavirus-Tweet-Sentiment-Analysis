# Coronavirus-Tweet-Sentiment-Analysis
## Problem Description
This challenge asks you to build a classification model to predict the sentiment of COVID-19 tweets.The tweets have been pulled from Twitter and manual tagging has been done then.
The names and usernames have been given codes to avoid any privacy concerns.
You are given the following information:
1. Location
2. Tweet At
3. Original Tweet
4. Label

## Approach

![image](https://user-images.githubusercontent.com/36273761/158756264-a379e4fd-1732-4267-999c-33b1d4783d98.png)

1. Familiarized and cleaned the data by doing preliminary analysis, and dealt with null values
performed EDA.
2. Removed html tags and unwanted words from the text data. Tokenization and stemming functions are applied.
3. Extracted hashtags belonging to different classes.
4. Used count vectorization for vectorizing the tweet text.
5. implemented multiple classification models for multi class classification.

## Technologies
* Python
* NLTK
* Textblob
* Pandas
* Google Colab
* Seaborn
* Matplotlib



## Result
I built a classification model that predicts the sentiment of tweets with an accuracy score of 78%.

