# CRYPTOCURRENCY PRICE AND MARKET
### Real-Time Market Trends & Volatility


## Overview/Introduction
Cryptocurrencies have emerged as a disruptive force in the financial world, offering decentralized digital currencies that operate independently of traditional banking systems. However, the cryptocurrency market is characterized by its inherent volatility, with prices fluctuating wildly within short periods.

Volatility is a measure of the rate at which the price of an asset fluctuates. In the context of the cryptocurrency market, it refers to the rapid and significant price movements experienced by digital assets.

## About Dataset 
[link as](https://www.kaggle.com/datasets/thedevastator/cryptocurrency-price-market-data)

The project uses two datasets representing the changes in prices of the various crytocurrency coins over 2 days. The two datasets have been combined to form one dataset for ease of analysis.

The dataset collects important data points such as the name of the cryptocurrency, symbol, price, hourly and daily change trends, 24 hour volume traded and market capitalization.

The dataset features:

1.'*Coin & Symbol*-Coins column represents the name of the various cryptocurrencies while symbol column represents the symbols for each other.The symbol column will enables the user to distinguish between coins with similar names (such as Bitcoin vs Bitcoin Cash).

2.*Price*- Price column represents the price each coin is trading for at any given time.

3.*1h,24h&7d*-1h, 24h and 7d columns are used to compare prices over time periods longer than one hour (for example from 1 hour ago to now or 7 days ago until today). This will give the user an indication of price volatility over time periods longer than one hour which can be used for forecasting market movement trends or as input in deep learning/neural networks models for predicting future price movements of various cryptocurrencies

4.*24h_voume*- 24h_volume gives volume traded in last 24 hours which helps users understand market momentum vis-a-vis volume traded during that period for cryptocurrency trading & understanding liquidity situation in any given period.

5.*mkt_cap*- The ‘mkt_cap’ column gives information about market capitalisation that shows how big/valuable a coin is & tells if its worth buying or not via comparison of current value & all available units combined together based on supply & demand forces at work in CryptoCurrency eco system.

6.*date: Date of the data entry. (Date)


## Problem Statement
Risk Assessment: The dataset is used to assess the risk associated with investing in different cryptocurrencies. This involves analyzing factors such as volatility, market capitalization, and trading volume.
The high volatility of the cryptocurrecy is both a characteristic and a challenge of this market, offering opportunities for profit but also exposing investors to substantial risks. Therefore this analysis is meant to show the trends of the various coins within a short period-2days. The analysis can be used to further build a future predictive model to assist in capping the high volatility of the coins.


## Findings
Price Fluctuations: The data clearly shows that the price of cryptocurrencies is highly volatile, with significant changes occurring within short periods (1 hour, 24 hours, 7 days).

Volume Impact: The trading volume, specifically the 24h volume has a direct impact on price changes. Higher trading volumes often correspond with more significant price swings, suggesting that large-scale buying or selling activities can drive up or down the price of a cryptocurrency.

Market Capitalization Correlation: There appears to be a correlation between market capitalization and price volatility. Cryptocurrencies with larger market caps generally exhibit higher volatility. This could be due to the increased influence these currencies have on market sentiment, and thus, their prices can be more sensitive to changes in market conditions.

Historical Trends: The historical data provides insights into the past performance of various cryptocurrencies. By examining price changes over different periods, we can identify trends and patterns that may inform future predictions.


## Business Recommendations

Investors should:
Understand Volatility: Given the high level of volatility in the cryptocurrency market, it's crucial to thoroughly understand what volatility means and how it impacts your investment strategy. Different cryptocurrencies may have different levels of volatility, and this can significantly affect your potential returns.

Monitor Trading Volume: The trading volume can provide valuable insights into the health of the market and the potential for price movement. Large increases in trading volume can signal a strong interest in a particular cryptocurrency, which could potentially lead to price increases.

Consider Market Capitalization: Cryptocurrencies with larger market caps tend to have higher volatility. Therefore, investors should be aware of the market cap of a cryptocurrency before investing.

Diversify Your Portfolio: Given the high level of volatility in the cryptocurrency market, it's recommended to diversify portfolio. This can help mitigate the risk associated with the volatility of individual cryptocurrencies.

Regular Monitoring and Adjustments: Regularly monitor your investments and be ready to make adjustments based on market changes. The cryptocurrency market is dynamic and can change rapidly.


## Future Work

Predictive Models: Develop more advanced predictive models to forecast future cryptocurrency prices. This could involve using machine learning algorithms to take into account more factors beyond just past prices.

Feature Engineering: Experiment with creating new features derived from existing data. 

Time Series Analysis: Apply time series analysis techniques to better understand the temporal dynamics of cryptocurrency prices. This could involve analysing seasonality, autocorrelation, and other aspects of the time series.
Network Analysis: Investigate the network structure of the cryptocurrency market. For example, examining how closely related the prices of different cryptocurrencies are, or how changes in one cryptocurrency's price affect others.
Real-time Updates: Implement a system to update the dataset in real-time, allowing for more timely analysis and predictions.
Integrating More Data Sources: Combine this data with other data sources, such as social media sentiment data, news articles, or other financial indicators, to get a more comprehensive picture of the market.


# Data source Acknowledgement

The data used in the analysis is obtained from Kaggle https://www.kaggle.com/datasets/thedevastator/cryptocurrency-price-market-data

