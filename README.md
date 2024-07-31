# Computational_Finance_for_Bonds_Issues


This is an Academic project Postgraduate in Data Science made in collaboration with my colleagues below:

- https://github.com/Przon | [Fernando Reis]
- https://github.com/lfbr0 | [Luis Ribeiro]
- https://github.com/renato747 | [Renato Morais]

## Overview

This is an academic project presented in the Data Science Postgraduate Program, which consists of financial data analysis, including constructing yield curves, analyzing historical stock data, and manipulating DataFrames.

TOOL: Python


## Activities and Techniques Covered

### 1.Building a YieldCurve class using The Bond Market Information: Matrix with information on maturity, price, and coupon for n bonds.

Methodology implemented:
  - Method to receive information about the bonds.
  - Bootstrapping discount factors using matrix operations.
  - Bootstrapping discount factors using a global solver.
  - Bootstrapping discount factors using an iterative procedure.
  - Determining the spot rate (annual compounding) for each maturity from the calculated discount factors and plotting them.
  - Determining the Yield to Maturity (YTM) for each bond and plotting them.
  - Determining the 1-year forward rate starting in each of the years from 1 to 9 and plotting them.
  - Plotting the spot rates, yields, and forward rates with a legend identifying the series.


DataFrame Manipulation:

Obtaining and Analyzing Historical Stock Data:
  - Obtaining historical data (closing price and volume) for 5 stocks using an API from 2012 to the present.
  - Plotting the cumulative returns of the stocks on a single chart.
  - Creating the correlation matrix of daily returns.
  - Saving the data (closing price and volume) to a CSV file for each ticker.
  - Loading the data from the saved CSV files into a single DataFrame with prices for each ticker.
