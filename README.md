# Financial-Planning-with-APIs-and-Simulations

An analysis of financial planning with the usage of APIs, Monte Carlo simulations, and confidence intervals.

Initial analysis determines the value of an individual's stock, bond, and crypto investment portfolio using Alternative.me and Alpaca API.

*    Note: The .env file was not uploaded for security reasons.
*    Users who will wish to test their own analysis must provide their own Alpaca Key ID and Secrety Key.

Secondary analysis is a 10 year and 30 cumulative return of the stock and bond portfolios using 500 Monte Carlo simulations and determing the results within a 95% confidence interval. 


---

## Technologies

This application runs on python version 3.7, with the following add-ons:

* [alpaca-trade-api](https://github.com/alpacahq/alpaca-trade-api-python) - For the importing of financial data from Alpaca.


---

## Installation Guide

Before using the loan qualifier application, the following packages must be installed:

*    pip install alpaca-trade-api


---

## Example

For a visual reference as to how the Monte Carlo simulations are calculated, please refer to the below images:

![Monte Carlo Cumulative Portfolio Return](images/5-4-monte-carlo-line-plot.png)

![Monte Carlo Cumulative Portfolio Histogram](images/5-4-monte-carlo-histogram.png)


---

## Contributors

Santiago Rosas

