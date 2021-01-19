# Distributed Data Sytems Group Project

Masters project focus on finding a correlation between twitter sentiment and cryptocurrency markets

[Updated Minute Resultion Crypto Data](https://www.kaggle.com/tencars/392-crypto-currency-pairs-at-minute-resolution)

## Team Members
- Berkay Canogullari
- Daniel Blessing
- Emre Okcular
- Evan Chen
- Mauro Napoli
- Ricky Zhang

### Project Goals

- Identify correlation between twitter sentiment through general hastags or large influencer accounts and price action for relevant coins
- Identify correlation between new coin listing annoucements on exchanges twitter aand price action for relevant coins
- Identify correlation between whale_alerts tweets about large cryptocurrency movements and price action for relevant coins
- Look for further correlations in financial markets

### Datasets 

Twitter sentiment using Developer API:
- **Historical Data**: Up to 10 days ago can query tweets using certain hashtags
- **Account Tweets**: Up to 1000 tweets from an account

Market Data:
- **Cryptocurrency trading pairs**: Historical trading data for 400+ coins minute candles
- **Coingecko API**: Historical data for every coin

### Roadmap

#### Vader Sentiment
Create method for analyzing input of tweets and outputting composite score.
Includes: data cleaning for tweets, averaging composite scores

#### Historical Price Data
Clean historical price coin data,
as well as create methods for pulling price data of coins not in original dataset

#### Identifying crypto pumps
Monitoring coingecko and creating and managing list of different crypto pump and dumps.
For a given day be able to identify the hourly coin price over the last 24 hrs.
Also for the data of the last 10 days

  
#### Querying twitter and grabbing historical tweets


#### Data wrangling twitter sentiment adn crypto pumps

#### Analyzing the twitter sentiment and crypto pumps together for trends

#### Visualizing data and final report
