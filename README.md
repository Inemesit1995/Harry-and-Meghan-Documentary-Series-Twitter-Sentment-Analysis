# Harry-and-Meghan-Documentary-Series-Twitter-Sentment-Analysis

# Introduction
The Duke and Duchess of Sussex explore the intimate days of their early courtship and the struggles that led to them feeling obliged to step aside from their full-time 
royal duties in Harry and Meghan, which is a two-volume, six-part documentary series.
The first three episodes of the first volume premiered on Netflix on Thursday, December 8, 2022, with the second volume following on Thursday, December 15, 2022. 
People all around the world have had conflicting views to the series, both on and off social media, particularly on Twitter.

# Basis for Analysis
The goal of this project is to carry out a sentiment analysis to measure the perception of Twitter users about this series.
To achieve my goal, i sought to answer the follwing questions:

1.	The popular hashtags
2.	The sentiments of users
3.	The location of most tweets

# Business Use Case
This sort of analysis can be useful to campanies for a variety of applications, such as marketing, customer service, product development, and public relations to 
understand how customers feel about their brand, products, or services, and to identify areas where they may need to improve their products or services. 


# Data Collection
I collected about 38,933 tweets along side the user's id, date and time of tweet, username, location of the user, retweets, likes using Twitter's API and Python 
library, tweepy. I also extracted hashtags from each tweets in order to have an insight of the popular hashtags. The duration of the data i collected was between 
15-12-2022 and 24-12-2022.

# Data Preprocessing
To ensure that data is clean, consistent, and in a format that is suitable for analysis and helps to improve the quality and reliability of the results, i carried out
the following data preprocessing steps:

1.  Data inspection for missing values and dropping of irrelevant columns
2.	Removal of mentions
3.	Removal of emojis
4.	Removal of punctuations
5.	Removal of hyperlinks
6.	Removal of stop words

# Analysis of Sentiments
Sentiment analysis is the process of using natural language processing and machine learning techniques to identify and extract subjective information from text. 
This can include determining the overall sentiment of a piece of text (positive, negative, or neutral), as well as identifying specific emotions and opinions 
expressed in the text. The polarity of user's sentiment lies between -1 and 1.

- If the polarity score is less than 1 (< 1), then the sentiment in negative
- If the polarity score is equal to zero (= 0), then the sentiment in neutral
- If the polarity score is greater than 1 (> 1), then the sentiment in positive

# Results and Insights
In the final analysis of the series, 45.35% of the tweets recorded positive sentiments, 24.47% were negative, and 30.18% of the users were neutral in their comments.

**#harryandmegannetflix** with about 5,000 tweets, 58,000 retweets, and 483,000 likes was the most popular hastag for the duration that tweets were scrapped.

Most of the tweets were made by users who did not specify their location. In the preprocessing step, i filled the missing locations with "Unspecified".
The unspecified location recorded tweets from 6,000 users 
