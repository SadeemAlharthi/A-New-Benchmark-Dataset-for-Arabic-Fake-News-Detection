# A-New-Benchmark-Dataset-for-Arabic-Fake-News-Detection
One of the problems faced concerning Arabic fake news detection is the scarcity of Arabic datasets. We believe it is important to available a dataset is written in the Arabic language explicitly created for this domain. The existing studies of Arabic fake news detection are limited because most of the dataset has not been available to access for research. We have built for the purpose of fake news detection the dataset of Arabic Fake News Tweets. 

# Dataset collection

- Only tweets content news in the Arabic language were collected from October 2020 until June 2021.

- We present a dataset AFNT: Arabic Fake News Tweets of 5,165 tweets. These tweets were collected directly from Twitter API by using Tweepy API can use our Scrape_Twitter notebook.

- We used two fact-checking accounts in Twitter to get classify news for real news and fake news were Anti-rumors Authority and Misbar.

- We used query texts to be given to the API to limit the stream of tweets got for each real and fake news post.

- The id_tweets.txt file contains a collection of AFNT tweets IDs only, and the id_label_tweets.csv file contains the dataset of already annotated tweets ids.
 
- For retrieving, the full object of the tweets consider the following tools Hydrator and Twarc.


# Dataset Statistics

The following statistics is from Tweets colected for nine-month between 1 October 2020 until 11 June 2021.
- The Number of Tweets: 5,165
- The Number of Fake news: 2,278
- The Number of Truth news: 2,887
- The Number of unique words: 90,017
- The Number of tweets with geolocation:  2,742

# Guideline to Hydrate

## Using TWARC Notebook

To hydrate the tweets_ID from our dataset Arabic Fake News Tweets you can use our Hydrate_TweetIDs_Arabic_Fake_News_tweets notebook.

The notebook runs on google collab
You are required to have a Twitter developer account
For those who prefer to use a Graphical User Interface (GUI) , We suggest using Hydrator.

## Using Hydrator

To use Hydrator follow the instructions in the Hydrator GitHub repository.


# Licensing

This dataset is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License (CC BY-NC-SA 4.0).By using this dataset , you agree to the terms of the LICENSE, and to all Twitter’s Terms of Service

# Contact

If you have any suggestions or questions, please reach out to sadeem1.alharthi on Gmail
