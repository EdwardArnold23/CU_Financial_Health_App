# Credit Union Financial Health App

## Background
My fintech consulting firm has built this tool to aid this large credit union's members evaluate their financial health. Members are able to assess their monthly budgets and then forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. 

**Please read the below instructions prior to running the financial-planner-checkpoint.ipynb**.

## Instructions:

- Create and add Alpaca API Key and Secret Key to the access.env file to access alpaca_trade_api
- Open and run each frame of the financial-planner-checkpoint.ipynb
	-Evaluated the client's total savings holding in Crytocurrency, Stocks and Bonds via 		Alpaca_trade_api
  	-Evaluate the Emergency Fund adequacy based on current aggregation of client's total 		savings
  	- Ran 3 separate term Monte Carlo simulations to using historical closing prices from 3 	years prior to model 500 possibilities for 30 years, 10 years and 5 years.
  	- Plot the probability distribution of each Monte Carlo simulations.
  	- Generate summary statistics for each Monte Carlo simulation.

  


