# Velocity of Money

This repository contains code and data to compare the velocity of M2 money stock (FRED's M2V series) to the theoretical velocity of money implied by the quantity theory of money (QTM).

## Sample Space

The data used in this repository includes FRED's M2V series, CPI, and GDP.

* [M2V](https://fred.stlouisfed.org/series/M2V)
* [CPI](https://fred.stlouisfed.org/series/CPIAUCSL)
* [GDP](https://fred.stlouisfed.org/series/GDP)

## MV = PT

where:

* M = Money Supply
* V = Velocity of Money
* P = Price Level
* T = Real Output (GDP)

Creates a dataframe with CPI, GDP, and M2 columns and then calculates the velocity of money by dividing CPI * GDP by M2. The calculated velocity is then compared to FRED's Velocity of M2 Money Stock.

## Results

The results of the analysis show that the velocity of money implied by QTM is generally close to FRED's Velocity of M2 Money Stock, but there are some discrepancies. In particular, the velocity implied by QTM is often higher than FRED's velocity. This could be due to a number of factors, such as the fact that FRED's M2V series does not take into account the velocity of money outside of the M2 money stock.
