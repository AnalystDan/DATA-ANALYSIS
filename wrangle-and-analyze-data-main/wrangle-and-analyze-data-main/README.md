# wrangle-and-analyze-data


# Introduction
The goal of this project is to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations.

# Data Used for Analysis
Enhanced Twitter Archive: Downloaded this file manually by clicking the following link: twitter_archive_enhanced.csv

Additional Data via the Twitter API: Each tweet's retweet count and favorite ("like") count at minimum, and any additional data you find interesting. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file. Each tweet's JSON data should be written to its own line. Then read this .txt file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count.

 Image Predictions File: Dog breed (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) is hosted on Udacity's servers and should be downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

# Steps
Data wrangling, which consists of: Gathering data Assessing data Cleaning data

Storing, analyzing, and visualizing our wrangled data

Reporting on 1) our data wrangling efforts and 2) our data analyses and visualizations
