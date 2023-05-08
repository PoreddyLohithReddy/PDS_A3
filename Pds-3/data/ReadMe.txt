The data file (Corona_NLP_test.csv) has a total of 834 missing values in the location column apart from that every other column doesn't contain any null values.
As all the operations for the dataset are being performed on OriginalTweet column, if we have to clean the data it is better to drop the location column completely
We can also leave the location column unchanged as it won't be used in this assignment.
Column \ Feature names:

UserName : The username of the twitter account that posted the tweet
ScreenName : The screen name of the twitter account
Location : Location of the twitter account that posted the tweet
TweetAt : The date and time of the tweet
OriginalTweet : The actual text of the tweet
Sentiment : The sentiment or polarity of tweet (Positive, Negative, Neutral)

The results folder contains the results of the process.
