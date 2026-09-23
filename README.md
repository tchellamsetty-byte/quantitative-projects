# Quantitative Projects

Risk modelling work from my BSc Financial Mathematics and Statistics at LSE.
Each folder contains the code and a short write-up covering the question, the
method, the result, and why it matters.

## Projects

**[Market Risk: VaR Backtesting and GARCH Volatility](./var-backtesting-garch)**
Documented fat tails, negative skew and volatility clustering in daily equity
returns using Jarque-Bera tests and squared-return ACFs. Backtested 99% and 95%
VaR under EWMA and historical simulation across the 2008 and 2020 crises, using
Kupiec coverage and Christoffersen independence tests. Compared eight GARCH
specifications on 26 years of S&P 500 returns.
*R, Quarto*


**[Estimation Risk: Covariance Conditioning in Portfolio Construction](./portfolio-covariance-conditioning)**
Built a rolling mean-variance optimiser for a 10-stock portfolio and diagnosed
covariance-inverse stability through condition-number analysis across 1, 5 and
10 year estimation windows.
*R*

**[Valuation Risk: Monte Carlo Engines and Variance Reduction](./monte-carlo-variance-reduction)**
Cut Monte Carlo estimator variance by 88.7% on a European call option using
importance sampling via a Girsanov change of measure. Benchmarked Euler-Maruyama,
Milstein and Richardson extrapolation against theoretical convergence orders.
*Python, group project*

## Tools

R (rugarch, quantmod), Python (NumPy, pandas, Matplotlib)

## Note

Academic work submitted at LSE. Shared for portfolio purposes.
