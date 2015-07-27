# Portfolio-constructor
 * Construct portfolios by constrained quadratic optimization --- minizing volatility, maxizing returns, and reducing over-fitting by encouraging to equally invest in all positions
 * Price data is sourced from Yahoo finance

## Frontend tested in Chrome 44 and Firefox 39
 * Some D3.js animation are turned off in Firefox.

## Backend written in Python 3.4, required the following libraries:
 * Cvxopt 1.1.7
 * Flask 0.10.1
 * Numpy 1.9.2

## Get start using the constructor
 * Run "python3 index.py" in terminal.
 * Open 127.0.0.1:5000 in a browser.
 * Select start- and end-date; add more tickers.
 * Click "Quote" to pull data and fit model.
 * Fit the model according to your risk-appetite.
 * Click red circles in the panel of "efficient frontier" to get constructed portfolios.

## (Over-)simplification about this constructor
 * Reinvest dividends
 * Ignore tax, commission fees, and price spreads and fluctuation in a day