# Cryptocurrency Dataset for Top 20 Cryptos

This dataset provides daily market data for the top 20 cryptocurrencies (by market capitalization at the time of data collection), including price, volume, technical indicators, and sentiment derived from Cointelegraph news. It also contains macroeconomic proxy data derived from the 5 cryptocurrencies. In addition, it now includes the raw Cointelegraph news data, enabling users to perform their sentiment analysis if desired.

## Overview

- **Time Frame:** January 1, 2021, to April 1, 2024
- **Purpose:** Supports research in technical analysis, sentiment studies, and macroeconomic comparisons within the crypto market.

## Data Fields

### Price & Volume
- Date, Open, High, Low, Close, Volume

### Technical Indicators
- Stoch_%K, Stoch_%D, Williams_%R, A/D Oscillator, Momentum, Disparity Index 7, ROC

### Sentiment Metrics
- positive, negative, neutral

### Macroeconomic Proxy Data (6 Cryptos)
For cryptocurrencies in the top 5, the Macroeconomic Proxy Data is calculated using the price history of the other five cryptos from the top 6. For all other cryptos, the proxy is based on the top 5 cryptocurrencies.
- **BTC:** Open_BTC, High_BTC, Low_BTC, Close_BTC, Volume_BTC
- **ETH:** Open_ETH, High_ETH, Low_ETH, Close_ETH, Volume_ETH
- **USDT:** Open_USDT, High_USDT, Low_USDT, Close_USDT, Volume_USDT
- **BNB:** Open_BNB, High_BNB, Low_BNB, Close_BNB, Volume_BNB
- **SOL:** Open_SOL, High_SOL, Low_SOL, Close_SOL, Volume_SOL
- **STETH:** Open_STETH, High_STETH, Low_STETH, Close_STETH, Volume_STETH

## Usage & Citation

Use this dataset for time series analysis, technical and sentiment studies, and as a macroeconomic proxy.

If you use this data in your research, please cite our paper:

```bibtex
@INPROCEEDINGS{10982029,
  author={Kumar, Amit and Ji, Taoran},
  booktitle={2024 IEEE International Conference on Big Data (BigData)}, 
  title={CryptoPulse: Short-Term Cryptocurrency Forecasting with Dual-Prediction and Cross-Correlated Market Indicators}, 
  year={2024},
  volume={},
  number={},
  pages={1-8},
  keywords={},
  doi={10.1109/BigData62323.2024.10982029}}
