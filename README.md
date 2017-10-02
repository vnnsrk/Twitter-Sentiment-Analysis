# Sentiment analysis and categorization of tweets using PySpark

Sentiment analysis is performed using unsupervised learning of word counts with the [Twitter API](https://developer.twitter.com/en/docs) data using PySpark. It was developed as a part of CSE 255 - Big Data mining and analysis course, in UC San Diego.

The goal of the project is to identify if we can detect the user partitions belonging to a specific political party or who favours a specific candidate.

## Dependencies
1. Python Twitter API warpper
2. PySpark
3. findspark
4. json - Python wrapper

## Data
1. The `data_input.txt` file consists of scraped data from Twitter
2. The `user-partition.pkl` file consists of the user partitions performed by unsupervised learning

# Execution 

`python twitter-sentiment-analysis.py`
