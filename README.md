CryptoCurrency analysis and black swan detection

## Team Member(s):
Anmol Gandhi, Harsh Mangal

# Monte Carlo Simulation Scenario & Purpose:
We are developing a model which attempts to predict future crypto based on historical opening and closing values. The model calculation is based on the GBM (Geometrical Brownian Motion) model which is used to predict values of stocks trading in the stock-market. We will do a box-cox transformation to attain some kind of normality. We will run a Monte-Carlo simulation by iterating through multiple historical data values and will forecast the value and try to determine what is the most likely price by fitting kernel density estimation function and further we are doing some detection regarding black swans

## Simulation's variables of uncertainty
We are using varibale like open and close and further use them to determine the daily volatility and other important features, we are using a normal distrubition by first appling box-cox transformation so that it becomes somewhat normal and then use monte carlo simulation further the forecasted values are converted using inverse box-cox transformation and later detect the blackswans using gumbel distribution.

## Hypothesis or hypotheses before running the simulation:
We think that cyrpto prices will generally increase drastically
we think blackswans are rare in crypo space

## Analytical Summary of your findings: (e.g. Did you adjust the scenario based on previous simulation outcomes?  What are the management decisions one could make from your simulation's output, etc.)
we came to know that after applying trasnformation the price doesnt show unnecessary exponential increase, this is important becasue we can come to know about most likely price. Also after blackswan detection we understood that the crypto space is highly volative and there is 93.4% probability that a black swan event could occur and this is a high risk level investment as the plot shows even -1000% daily changes in a number of cryptos.

## Instructions on how to use the program:
It is an ipython notebook and instruction on which function to use first is given inside the notebook.

## All Sources Used:
Geometric Brownian Motion: https://www.investopedia.com/articles/07/montecarlo.asp 

Tarnopolski, Mariusz. (2017). Modeling the price of Bitcoin with fractional Brownian 	motion: a Monte Carlo approach. 

Cocco, L., Pinna, A., & Marchesi, M. (2017). Banking on Blockchain: Costs Savings Thanks 	to the Blockchain Technology. Future Internet, 9(3), 25.

kaggle.com

yahoo finance ticker.

Gumbel and Black swan: http://www.quantatrisk.com/2014/03/01/extreme-var-for-portfolio-managers/
