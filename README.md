# Binance Trading bot v1 

## This code is to demonstrate below functionalities: 


#### A good trading bot needs a great entry strategy and a precise exit strategy. I have played around with a few techniques starting from different period moving averages, Relative Strength Index (RSI), Bollinger Band and also the ensemble strategy of all these three. The one which is incorporated in the code is ensemble strategy. This has given a decent return during one week’s run but when combined with far superior strategies would lead to higher returns.
#### Below code demonstrates a Python integration to Binance exchange and fires an order to buy/sell based on your entry/exit strategies. The code imports the last x days of data, in this case the last 30 days of data (from 15 minutes candles) of top 200 crypto currencies based on its market cap. In the code I have also given lower weightage to the high value currencies per unit to avoid few currencies so that I can increase my profitability.

##### **Data flow through APIs:** helps getting the data from Binance to destination through APIs 
##### **Flow delta data:** Gets the delta data from last iteration till current time 
##### **Alt for investment:** Identifies the right crypto for investment 
##### **Order caller:** Places order and confirmation 
##### **Exit enter:** Evaluates the margin and make decision to sell 
##### **Bonus:** Telegram alert on buy/sell : Send feed into telegram channel or individuals for notification 
