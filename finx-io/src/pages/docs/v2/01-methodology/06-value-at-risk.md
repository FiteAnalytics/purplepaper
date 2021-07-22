---
title: Value at Risk
tags: value-at-risk, regulations, documentation
---
# Value at Risk
Value at Risk (VaR) is a measure of expected loss at a specific confidence interval over a specific horizon.
The Fite Platform can run all VaR implementations (parametric, historical, & Monte Carlo), but our default is to use Monte Carlo calibrated by the historical time series of the portfolio, related securities, and other benchmarks. Our VaR calculations on securities and portfolios are highly configurable, accommodating a variety of stress tests and other techniques in risk management, such as SEC Rule 18f-4 for hedge funds holding derivatives.
# SEC Rule 18f-4 Services
Fite Analytics provides complete Rule 18f-4 Value at Risk calculations across all asset classes and security types. Our services
are tailored to each financial institution's needs, but most of our 18f-4 services include the following:
- Daily portfolio holdings submitted to the cloud (SFTP, Amazon S3, or email)
- Fite Analytics calculates VaR and other risk measures and returns spreadsheets and PDF reports
- Fite Analytics periodically produces compliance and other Risk Manager reports in support of documented risk managemement program
- Fite Analytics creates custom benchmarks, runs scenarios and performs backtesting
## Inputs into Calculations
1. Fund positions at close of each trading day (security id, holding amount, security market price is optional but generally provided)
2. Stress testing parameters
3. Horizon
4. Back-testing window
5. Calibration frequency
## Work Products Generated
1. Daily VaR for each security and for portfolio as a whole
2. Daily VaR for benchmark
3. Daily VaR report comparing portfolio and benchmark, with compliance notes
4. Weekly Stress Test of portfolio
5. Weekly Stress Test report including cumulative through-time analytics
6. Monthly or Quarterly calibration