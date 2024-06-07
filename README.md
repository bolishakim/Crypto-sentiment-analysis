# Crypto Sentiment Analysis: Unveiling the Market Trends through Sentiment Exploration

## Introduction
This project analyzes the sentiment of Reddit comments related to Bitcoin and examines their relationship with Bitcoin's market price and trading volume.

## Motivation and Research Questions
- Do Reddit comments affect Bitcoin trading volume and price development?
- What is the relationship between Reddit sentiments and Bitcoin traded volume?
- What is the relationship between Reddit sentiments and the actual Bitcoin market price?

## Data Retrieval
Data was collected from two subreddits: `r/Bitcoin` and `r/BitcoinMarkets` using the `PRAW` package. Bitcoin market data was retrieved using the `CCXT` package.

## Data Processing
Data was cleaned and processed to remove noise. Only relevant comments were retained based on a set of keywords.

## Data Analysis
Sentiment analysis was performed using `VADER` and `BERT`. The relationship between sentiment and market data was evaluated using regression analysis.

## Conclusion
There is a positive relationship between Reddit sentiment and Bitcoin market trends. BERT showed a higher correlation compared to VADER.

## Repository Structure
- `README.md`: Project documentation.
- `Accuracy/`: Contains accuracy evaluation files for sentiment analysis.
- `Data/`: Contains data files used in the project.
- `BERT_Sentiment.py`: Script for performing sentiment analysis using BERT.
- `BERT_daily_analysis.py`: Script for daily analysis of BERT sentiment data.
- `Cryptocurrency_Fun.py`: Script for retrieving cryptocurrency market data.
- `Reddit_data_Fun.py`: Script for retrieving Reddit data.
- `VADER_Sentiment.py`: Script for performing sentiment analysis using VADER.
- `VADER_daily_analysis.py`: Script for daily analysis of VADER sentiment data.
