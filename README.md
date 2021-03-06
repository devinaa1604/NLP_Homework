# Crypto Prices Using NLP

![Stock Sentiment](Images/sentimental.jpeg)

## Introduction

I have applied natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I have also applied fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

------

### Instructions

#### Sentiment Analysis

Used the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

Used descriptive statistics to answer the following questions:

> Which coin had the highest mean positive score?
> Ethereum
> Which coin had the highest negative score?
> Bitcoin
> Which coin had the highest positive score?
> Bitcoin

#### Natural Language Processing

I have used NLTK and Python to tokenize the text for each coin. I have:

1. Lowercase each word
2. Remove punctuation
3. Remove stop words

Next, looked at the ngrams and word frequency for each coin.

1. Used NLTK to produce the ngrams for N = 2.
2. Listed the top 10 words for each coin.

Finally, generated word clouds for each coin to summarize the news for each coin.

![btc-word-cloud.png](Images/btc-word-cloud.png)

![eth-word-cloud.png](Images/eth-word-cloud.png)

#### Named Entity Recognition

Here I have built a named entity recognition model for both coins and visualize the tags using SpaCy.

![btc-ner.png](Images/btc-ner.png)

![eth-ner.png](Images/eth-ner.png)
