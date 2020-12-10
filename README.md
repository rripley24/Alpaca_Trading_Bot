# Alpaca Trading Bot with AWS Chalice & TradingView Webhooks

## 12-8-20
### Group:
 * Sheldon Harracksingh
 * Xavier Spurlock
 * Richard Ripley
 
 ![Algo Trading image](https://www.tradersdna.com/wp-content/uploads/2016/10/algorithmic-trading.jpg)
 
# Objective:

**TO MAKE MONEY!!!** By backtesting simple trading strategies (such as SMA/EMA) against 3 known stocks (SPY, QQQ, & AAPL) to observe which yield the most profitable returns for future deployment. Then, initiate a trading bot utilizing: Python, AWS Chalice, TradingView, and link it to our Alpaca Paper Trading Account. We are hoping to launch a successful algo trading bot which can execute simple trades while we are busy with work, school, or life. 

**What *is* day trading?** - please see article from [Investopedia](https://www.investopedia.com/articles/trading/05/011705.asp) eloquently explaining how stock trading works. 

# Applications & Resources:

Before we began, we needed to download the following apps in order to achieve our objective:

1 - [Alpaca](https://alpaca.markets) for our online brokerage/paper trading account

2 - [Insomnia Rest](https://insomnia.rest) allowed us to test our AWS Chalice on a local network

3 - [Amazon AWS](https://aws.amazon.com) to create a resting URL with AWS Chalice

4 - [TradingView](https://www.tradingview.com) for researching stocks and creating alerts utilizing Webhooks which succesfully bought our stocks 

   * **Resources:** We found this "hacking the markets" [Github page](https://github.com/hackingthemarkets) to be extemely useful with troubleshooting the launch of our trading bot. 
   
# Process:

**See attached Notebook files for our Backtrader charts and how to successfully deploy and launch our trading both with Chalice**

After backtesting the Simple Moving Average Strategy and Exponential Moving Average Strategy on SPY, QQQ, and AAPl, we found that the 3 EMA strategy of 9, 21, & 55, respectively, provided the most profitable returns over a 4 year window. With a starting balance of $100,000 our 3 EMA strategy gave us a 62% return on ticker: QQQ; which isn't half bad for such a basic strategy. Knowing this, we looked up QQQ in TradingView and confirmed that it was trading above our 3 EMA lines, so we deployed our trading bot and successfully purchased 1 stock based on the alert parameters we initiated (we set sell instructions if our stock hits a certain price for profit vs loss). Now we can continue to execute trades with differing stipulations of our choosing and monitor the gains vs losses in our paper trading account to iron out any flaws, and continually test prior to linking a proper brokerage account with real funds. 

# Live Demonstration: 

**Please see the [Youtube Link](https://www.youtube.com/watch?v=rRJ36R7YbCA&feature=youtu.be) of the recorded live deployment of our bot. We wanted to demonstrate how easily it can be used when the markets are open to execute trades.**

# Conclusion: 

After experimenting with Backtrader, our paper trading account, and TradingView, we only want to further test more elaborate trading strategies with our Bot. Admittedly, these simple strategies are not as aggressive as we would like; however, it has been a great success to launch this bot to set the foundation for future trades. We did a ton of investigating other trading strategies and would love to find a way to deploy a bot that understood the [Ichimoku Could Strategy](https://tradingstrategyguides.com/best-ichimoku-strategy/), or the [3 Bar Reversal and Go](https://tradingsim.com/blog/three-bar-reversal-and-go/). Our goal is to continue working on this bot and improving it so we can earn side income to better our quality of life. 
