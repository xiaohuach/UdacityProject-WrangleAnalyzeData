# UdacityProject-WrangleAnalyzeData

This project is an exercise of data cleaning, accessing and illustration. It is based on tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.
3 sources of data is downloaded, extracted and combined:
* The WeRateDogs Twitter archive: twitter_archive_enhanced.csv
* Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt
* Tweet image predictions file image_predictions.tsv
cleaned final version of dataset is in tweeter_archive_master.csv
See wrangle_report.pdf for descriptions of the data wrangling process.
See act_report.pdf for descriptions of data analysis and visualization results.
