Creating Twitter developer account and collecting data from Twitter using Twitter API.
(a)	Open a Twitter developer account.

•	I have created a Twitter developer account using my email id and password. Also, I generated the API key and secret, bearer token, access token, and secret, all of which are required to connect to my Twitter account through the Twitter developer's API. Also, I created a config.ini file to store the variables app_key, app_secret, oauth_token, and oauth_token_secret.

(b)	Collect the latest 10 Tweets from your Twitter account. You should also use filters (ex. COVID)

•	By using the config.ini file I have initialized the object of tweepy module which points to my twitter developer account. Also, to perform operations such as getting all the tweets up until now and searching for a specific hashtag, it is required to have elevated access to the Twitter developer account. Now the API object of the tweepy contains multiple functions in its arsenal. The fundamental function that is required to extract all the tweets from the user’s account is home_timeline(), which will return all the tweets from the Twitter account.
•	To get the specific tweets from the search_tweets() function is used in the notebook. For example, I have used the “#Disney” string to search for all the tweets related to Disney.

(c)	 Print the full text for these tweets

•	The full text of these tweets can be found by looping over the metadata acquired while calling upon the home_timeline() function and the search_tweets() function, and accessing the text property of the said metadata.
Overall, by performing this activity I got to learn about the functionality of the developer API of the twitter and how it can be used to acquire various tweets from the user account as well as twitter database. I find it as one powerful example of how one can perform data mining.

References:
•	Quantitative Finance &amp; Algo Trading Blog by QuantInsti. (2022, July 11). How to get tweets using Python and Twitter API. Quantitative Finance &amp; Algo Trading Blog by QuantInsti. Retrieved January 29, 2023, from https://blog.quantinsti.com/python-twitter-api/
•	Twitter. (n.d.). Getting access to the Twitter API | docs | twitter developer platform. Twitter. Retrieved January 29, 2023, from https://developer.twitter.com/en/docs/twitter-api/getting-started/getting-access-to-the-twitter-api 
