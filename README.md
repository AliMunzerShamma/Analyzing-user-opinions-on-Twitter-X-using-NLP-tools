# Analyzing-user-opinions-on-Twitter-X-using-NLP-tools

Tweets are collected from Twitter over a specific period of time (e.g., a week) and analyzed to identify the most trending topics.

Several operations are subsequently performed on the collected data:

1-Data Collecting:
  Collect at least 500 tweets from Twitter users in Saudi Arabia on specific dates using GetOldTweets library.

2-Text Cleaning:
  The goal of this section is to clean the data and make the tweet texts as uniform as possible,
  First, the tweet text is extracted from the rest of the irrelevant data, such as links or images, which should be disregarded.

3-Normalization:
  A series of operations are performed to standardize the text format, such as converting the hamza to an alif, changing the ta marbuta to a ha, removing repeated letters, and so on.

4-Text Analysis:
  A series of operations are performed to analyze the collected texts by identifying groups of words that frequently appear together in the studied text (e.g., pairs, triads, etc.) 
  and detecting less common words, which may indicate spelling errors.

5-Trending Topics:
  Find the most popular hashtags in the collected data.


