# Data-Wrangling

# Wrangling and Analyze Data
## Demilade Aliu


## Summary

This project provides focuses on wrangling of the ratings of dogs from a Twitter handle WeRateDogs. In the development of the project, the Gather-Assess-Clean approach was adopted for the wrangling process. This twitter account consists of pictures of various dogs and their ratings. The datasets used include 'image predictions', 'twitter_archive', 'tweet_json. Each datasets was cleaned and merged to get a master dataset. Upon completion of wrangling the master dataset was analyzed and visualized to share some useful insights.

## Note
Cell 6 should be skipped as Twitter API keys and tokens was not included for security purpose, however the output of cell 6 is available in the repository as tweet-json

## Tools and libraries
For this analysis, python programming language was used on jupyter notebook frame with libraries such as pandas, matplotlib, numpy, seaborn, tweepy

## Files
Files in th repository include;
- wrangle_act.ipynb: A jupyter notebook file that contains the python code
- wrangle_report.html: An html document that explains the data wrangling efforts
- act_report.html:  An html document that communicates all the insights and displays the visualization(s) produced from the wrangled data.
- twitter-archive-enhanced.csv: csv file that contains basic information about 2356 tweets
- tweet-json.txt: Twitter API was queried for each tweet's JSON data using Python's Tweepy library and stored each tweet's entire set of JSON data in a file called   tweet_json.txt file.
- image-predictions.tsv: This file (image_predictions.tsv) is present in each tweet according to a neural network. It is hosted on Udacity's servers and was downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv
- twitter_archive_master.csv: master dataset that contains merged data from each data set upon cleaning



