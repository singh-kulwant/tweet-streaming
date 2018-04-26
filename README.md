# twitter streaming
# Getting Credentials
to use twitter api, need to have few credentials

The consumer key/secret is used to authenticate the app that is using the Twitter API, 
while the access token/secret authenticates the user. 
store them in a JSON file "twitter_credentials.json" and load these values from your code when needed.

we will use  twython library because of its diverse features aligned with different Twitter APIs

we'll use the Search API to search tweets containing the string "random_text"
later more realistic example using Twitter's Streaming API.
