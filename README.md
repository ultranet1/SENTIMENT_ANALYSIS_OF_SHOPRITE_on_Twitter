# Sentiment-Analysis-of-Shoprite-in-december-2020
# OBJECTIVE
This project is aimed at analyzing:
* Tweeps (twitter user's) emotion about shoprite
* Most occurring words in tweets
* Top Tweeps on ShopRite trend table.
 

# METHOD
The method is to use Tweepy API to scrape relevant tweets from twitter,
(Unfortunately twitter restricted the maximum scrap tweets to 2-3000 per day).
The tweets are parse using Regex&Nltk. TextBlob is used to analyze Sentiment polarity. 
While Seaborn & Wordcloud is used to visualize the analysis.
