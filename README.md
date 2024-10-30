# Twitter Sentiment Analysis

This Python project fetches recent tweets about a specified topic, performs sentiment analysis on each tweet using TextBlob, and calculates the percentage of positive, negative, and neutral sentiments. The code also displays a sample of the positive and negative tweets.

## Features

- Connects to Twitter's API to fetch tweets based on a search query.
- Cleans tweets by removing links, mentions, and special characters.
- Classifies the sentiment of each tweet as positive, negative, or neutral using TextBlob.
- Calculates and displays the percentage of positive, negative, and neutral tweets.

## Prerequisites

- **Python 3.x**
- **Twitter Developer Account**: You need a Twitter Developer Account to access the API keys and tokens required for authentication.
- **Libraries**:
  - `tweepy`: For accessing Twitter's API.
  - `textblob`: For performing sentiment analysis.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/FarhanRex/twitter-sentimental.git
   cd twitter-sentimental
   pip install tweepy textblob
Obtain Twitter API Credentials:

Go to Twitter Developer and create an app.
Obtain the API Key, API Key Secret, Access Token, and Access Token Secret.
Replace the placeholders in the code with your own credentials.
Usage
Edit the Code:

Open twitter_sentiment_analysis.py and replace XXXXXXXXXXXXXXXXXXXXXXXX with your actual Twitter API keys and tokens.
