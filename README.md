# Binance-EDA
EDA on Cryptocurrencies using Binance API
 
 
## Goal & Context:
Retrieve data on BTC using the Binance API and conduct an initial EDA of the data.

## Steps: 
 * Leverage the [Binance API](https://www.binance.com/en/binance-api) to gather data 
 * Preprocess & Explore the data using Pandas
 * Plotting recent data points on the specific crypto of interest using [mplfinance](https://github.com/matplotlib/mplfinance) 
 
 Full steps in details within my **[Jupyther notebook](https://github.com/Oussamahajoui/Binance-EDA/blob/main/Binance_EDA.ipynb)**

## Findings:
The last 250 days chart for BTC-USDT shows the following trends:
![image](https://github.com/Oussamahajoui/Binance-EDA/assets/83676274/73fae232-6147-4c88-8a9e-2aa7cb515f10)

As we can see:
* The overall trendline is going up, in spite of the recent dip
* The volumes seem to have dropped drasticly recently
* A trading strategy could be developped by leveraging the Moving averages & the volume data we see.

## Limitations:
There are several limitations to consider in this analysis, including:

* The analysis is based on data from a single exchange (Binance), which may not be representative of the broader cryptocurrency market.
* Although we retrieved data from all the way back to Jan 2008, the data only includes the BTC-USDT pair, and the analysis was only performed over the last 250 days, which may not capture longer-term trends or movements in the market.

## Next steps:
The data collected and plotted, could be used to:
* Further analysis on crypto trends specific to the currency
* Trading algorith development


## Conclusion:
In conclusion, this project provides a high-level analysis of the current trends and movements in the cryptocurrency market using Binance API data. The findings highlight potential trading strategies that could be developed using the moving averages and volume data. This analysis could serve as a starting point for further research and analysis on the cryptocurrency market.


###### Made by Oussama Hajoui
