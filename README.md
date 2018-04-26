CryptoCurrency Trade pair analysis

## Team Member(s):
Anmol Gandhi, Harsh Mangal

# Monte Carlo Simulation Scenario & Purpose:
We are developing a model which attempts to predict future Litecoin and ripple values based on historical opening and closing values of litcoin and ripple wrt USD and BTC.. The model calculation is based on the GBM (Geometrical Brownian Motion) model which is used to predict values of stocks trading in the stock-market. We will do a box-cox transformation to attain some kind of normality. We will run a Monte-Carlo simulation by iterating through multiple historical data values and will forecast the value with each trading pair and try to determine which trading pair would have been more useful more investment. We will do this fo both ripple and litecoin trading pairs with btc and usd

## Simulation's variables of uncertainty
We are using varibale like open and close and further use them to determine the daily volatility and other important features, we are using a normal distrubition by first appling box-cox transformation so that it becomes somewhat normal and then use monte carlo simulation further the forecasted values are converted using inverse box-cox transformation.

## Hypothesis or hypotheses before running the simulation:
We think that ripple and litecoin prices will increases in btc as well as usd

we think that ripple litecoin wrt usd will be more profitable because of high volume of trades

## Analytical Summary of your findings: (e.g. Did you adjust the scenario based on previous simulation outcomes?  What are the management decisions one could make from your simulation's output, etc.)
We are yet to still perform this, We are still reading papers and articles to determine some better adjustment to our calculation formula

## Instructions on how to use the program:
Will be up soon

## All Sources Used:
Geometric Brownian Motion: https://www.investopedia.com/articles/07/montecarlo.asp 
Tarnopolski, Mariusz. (2017). Modeling the price of Bitcoin with fractional Brownian 	motion: a Monte Carlo approach. 
Cocco, L., Pinna, A., & Marchesi, M. (2017). Banking on Blockchain: Costs Savings Thanks 	to the Blockchain Technology. Future Internet, 9(3), 25.
Cocco, L., Pinna, A., & Marchesi, M. (2017). Banking on Blockchain: Costs Savings Thanks 	to the Blockchain Technology. Future Internet, 9(3), 25.

kaggle.com
yahoo finance ticker.


