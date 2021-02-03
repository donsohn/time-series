# time-series

Using time series I wanted to explore some predictive models and understand how things worked under the hood.  
To make it easier on myself I first explored using Facebook's Prophet, then subsequently with SARIMA.  Both methods would forecast trends and seasonality, which I was especially interested in observing for stock price x time.  
As bonus, I wanted to create visualization other than the plots I have normally been doing via Python libraries.  To that end I used Tableau Public which is Tableau's free offering for creating and sharing visualizations.

Steps:
- Sourcing stock prices with yfinance Python library.  
- Applied Facebook Prophet for time series prediction
- Applied SARIMA for time series prediction 
- Viz using Tableau Public

https://public.tableau.com/profile/don.sohn#!/vizhome/TimeSeries_16119756574140/prophetdash

As with all projects I've worked on, there was a wish list of related things to try and investigate:
- Use TabPy (Python library for Tableau) to leverage machine learning in Tableau, however I believe this requires paid Tableau licensing.
- Asset correlation in context of overall portfolio mix and diversification.  Taking one's portfolio of investments to see how assets correlate with each other e.g. if not correlated then won't move in tandem with market down movements, which could mitigate risk in portfolio. 
- Taking the above idea a step further, applying this to mutual funds along with time series to understand seasonality.  Based on the portfolio makeup of the fund, be able to predict at next rebalancing what instruments will be changed and compare the result for accuracy.
- More viz and story telling in Tableau and/or Power BI
- Deeper understanding of the calculations and interpretations behind time series e.g. autocorrelation factor, multiplicative seasonality, uncertainty, etc.
