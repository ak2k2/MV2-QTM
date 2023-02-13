# Velocity of Money

This repository contains code and data to compare the velocity of M2 money stock (FRED's M2V series) to the theoretical velocity of money implied by the quantity theory of money (QTM).

## Sample Space

'MV2-QTM/data' contains FRED's M2V series, CPI, and GDP.

* [M2V](https://fred.stlouisfed.org/series/M2V)
* [CPI](https://fred.stlouisfed.org/series/CPIAUCSL)
* [GDP](https://fred.stlouisfed.org/series/GDP)

## QTM => MV = PT
* M = Money Supply from (M2SL.csv)
* V = Velocity of Money
* P = Price Level (CPI) 
* T = Volume of Transactions (GDP)

Creates a dataframe with CPI, GDP, and M2 columns and then calculates the velocity of money (V=PT/M) by normalizing and then taking (CPI x GDP / M2SL).

## Results

The velocity of money implied by QTM is compared with FRED's Velocity of M2 Money Stock

* FRED's M2V series does not take into account the velocity of money outside of the M2 money stock.


[quantity-theory-of-money](https://www.investopedia.com/insights/what-is-the-quantity-theory-of-money/)
