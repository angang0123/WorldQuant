# Submission 1: Basic Statistics, Linear Regression, and Univariate Analysis
This submission requires you to implement linear regression in forecasting and analysis. Linear regression represents a basic econometric tool and it is the starting point for a variety of prediction models such as ARMA and non-linear algorithms. You will also use the Box-Jenkins approach for selecting the optimal parameters of ARMA forecasting model. Exogenous variables, which improve model forecasts, must be indicated at the end of this submission, to combine with finance theory and research.

## Basic Statistics
Download JP Morgan stock historical prices from Yahoo Finance with the following characteristics:
  o Period:February1,2018–December30,2018
  o Frequency:Daily
  o Priceconsideredintheanalysis:Closepriceadjustedfordividendsandsplits
Using this data and R as the programming language, calculate the following:
  1. Average stock value
  2. Stock volatility
  3. Daily stock return
Using the same data above, calculate the following in Excel (you can use OpenOffice as an alternative to Excel):
  1. Average stock value
  2. Stock volatility
  3. Daily stock return
  4. Show JP Morgan stock price evolution using a scatter plot
  5. Add a trendline to the graph (trendline options – linear)

## Linear Regression
  1. Implement a two-variable regression in R language using the following data: o Explainedvariable:JPMorganstock(adjustedcloseprice)
    o Explanatoryvariable:S&P500
    o Period:February1,2018–December30,2018
    o Frequency:Daily
  2. With the same variables as above (JP Morgan Stock and S&P500), implement a two-
variable regression in Excel using LINEST function and Analysis ToolPak. 

## Univariate Time Series
Download the following data:
  o Datasource:https://fred.stlouisfed.org/series/CSUSHPISA
  o Periodconsideredintheanalysis:January1987–latestdata 
  o Frequency:monthlydata
With this data, do the following using R or Python languages:
  1. Forecast S&P/Case-Shiller U.S. National Home Price Index using an ARMA model.
  2. Implement the Augmented Dickey-Fuller Test for checking the existence of a unit root in Case-Shiller Index series.
  3. Implement an ARIMA(p,d,q) model. Determine p, d, q using Information Criterion or Box- Jenkins methodology. Comment the results.
  4. Forecast the future evolution of Case-Shiller Index using the ARMA model. Test model using in-sample forecasts.
Write a report where you research and suggest types of exogenous variables that can improve forecasts. In your references, indicate four (4) research articles or books at minimum.

## Submission Requirements
Submit the following documents for your assignment:
  • A 500-word report in PDF format, must be separate from the other documents
  • Excel spreadsheets
  • Source code if applicable. Include comments to explain how the code runs
Note: The PDF file with your report must be uploaded separately from the zipped folder that includes your other files. This allows Turnitin to generate the similarity report.
