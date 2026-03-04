# 🤖 ML BTC

ML BTC is a machine learning project for Bitcoin price analysis.  
It predicts 3 long-term zones : 
- Buy zone: favorable for buying
- Sell zone: favorable for selling
- Neutral zone: hodl

⚠️ This model is experimental and **we are not responsible for any financial loss**. Use at your own risk.

## Datasets

- **Bitcoin historical data** from kaggle : https://www.kaggle.com/datasets/adilshamim8/bitcoin-historical-data
- **Fear and greed index** from alternative.me API : https://api.alternative.me/fng/

## Labeling

The current dataset does not contain any labels, so the following labels are assigned to each row based on defined periods:
- Buy zone: favorable conditions for buying
- Sell zone: favorable conditions for selling
- Neutral zone: hold (HODL)

## Additional indicators

- 14-period weekly RSI
- 200-period weekly SMA