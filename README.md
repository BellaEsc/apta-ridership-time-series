# apta-ridership-time-series
This repository includes a time series analysis of [ridership data from the American Public Transportation Association (APTA)](https://www.apta.com/research-technical-resources/transit-statistics/ridership-report/) which was compiled by Matthew Dickens (Director of Policy Development and Research). The data includes quarterly reports of unlinked passenger trips from U.S. and Canada transportation agencies. I've also used data obtained from the [Bureau of Economic Analysis (BEA)](https://www.bea.gov/) for part of my analysis; specifically, I will be using a table containing quarterly GDP information for the state of California which was downloaded [here](https://apps.bea.gov/regional/downloadzip.cfm).

The first part of the analysis involves fitting seasonal ARIMA models to two time series: the first series is the total ridership across all public transportation modes and agencies (U.S. and Canada) which I refer to in the report as APTA, and the second series is bus ridership data for the Orange County Transportation Authority (located in California) which I refer to as OCTA in the report. Both are from the same data set mentioned above. 

The second part of the analysis includes fitting an ARMAX model to the OCTA series with the added variable of California GDP to see how the multivariate model changes the forecasting.

