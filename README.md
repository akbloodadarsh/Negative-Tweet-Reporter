# Negative-Tweet-Reporter-(Terminal)

#### Follow The Steps
### 1. Insert Your Twitter Credentials in `twitter_credentials.py`
### 2. Run the `test.py`
### 3. Enter the hashtag you want to target.Ex:- #NameOfHashtag
### 4. Let the program fetch and analyse the tweets
### 5. When it will encouner a negative tweet it will ask for you to analyse the tweet and if in your perspective it is a negative tweet, you can press y to report it!
### 6. Then the process will resume

#### How this is happening

I have provided a GUI for interaction & I have used training dataset to train a model using multinomial naive bayes,then the program is fetching 10 tweets at a time(Their is a limit of 3200 because Twitter allows a maximum of 3200 tweets for extraction).Then the tained model will analyse the tweets and if it encounter a negative tweet then I am asking the user to analyse the tweet and if from his perspective the tweet is negative too,then he can verify it and the program will report it!
(The program is only fetching the tweets which are using english language)
