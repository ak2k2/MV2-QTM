## Armaan Kapoor, Quantity Theory of Money vs M2V
# Velocity of Money
The velocity of money implied by QTM can be expressed as:

$$ V=\frac{PT}{M} $$

Where: 

* $M$ is the Money Supply from (M2SL.csv)
* $V$ is Velocity of Money
* $P$ is the Price Level (CPI) 
* $T$ is the Volume of Transactions (GDP)

## DATA
This repository contains code and data to compare the velocity of M2 money stock (FRED's M2V series) to the theoretical velocity of money implied by the quantity theory of money (QTM).

'MV2-QTM/data' contains FRED's M2V series, CPI, and GDP.

* [M2V](https://fred.stlouisfed.org/series/M2V)
* [CPI](https://fred.stlouisfed.org/series/CPIAUCSL)
* [GDP](https://fred.stlouisfed.org/series/GDP)

## MISC.

The trailing mean squared error (MSE) of QTM vs M2V is 

$$ MSE = \frac{1}{N}\sum_{i=1}^{N}{\left(V_{QTM} - V_{M2V}\right)^2} $$

* Almost consistently increasing, sugggesting that QTM models ability to explain effects in M2V is diminshing.

## SOURCES 
[what-is-the-quantity-theory-of-money](https://www.investopedia.com/insights/what-is-the-quantity-theory-of-money/).
