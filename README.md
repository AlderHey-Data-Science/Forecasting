# Forecasting Time Series Templates



## Project Description
This project aims to explore and address univariate time series forecasting through the use of different algorithms, some new such as XGBoost 
and Prophet amongst older trusted models such as Linear Regression and ARIMA. These models will be in template format allowing the users of 
these templates to load in their relevant data, define specific variables meeting the needs of their data and get predictions for their target 
variable automatially output to csv. Asides from isolated models Python Time Series libraries will also be investigated, these being sktime, AutoTS
& Darts. After which an evaluation can be drawn to see what models and or packages perform the best across a range of time-scaled data from monthly, 
daily and hourly data. This will then hope to give users insight into what model or package best suits their data and what model / package is the most 
trusted.

## Time Series
Simply put, time series data is data that is measured across a certain time scale, for example, seconds, minutes, hours, days, weeks,
months, years and so on. Some scripts require us to transform time series data into supervised learning data. To turn time series data 
into a supervised learning problem it must be processed through the 'Sliding Window' technique. The sliding window technique uses previous 
time steps as input variables and use the next time step as the output variable.

## Stationarity
Stationary usually refers to time series data. A time series is stationary if it has no trend/drift i.e. it means that the data stays roughly constant over time. It's important your data is stationary, not only is it easier to analyse & predict a dataset with stationarity. If a series is consistently increasing over time, then the sample mean and variance will also grow with the size of the sample, and your model or the proposed time series solution will always underestimate the mean and variance in the furture periods. 
* To check for stationarity there are a number of tests we can do, these include:
1. Augmented Dickey Fuller Test (ADF)
2. Kwiatkowski Phillips Schmidt Shin Test (KPSS)
3. Differencing 

See 'stationarity_check' script in 'Forecasting' repo for more on checking that your data is stationary.

## Seasonality 
A recurring pattern with a defined and predictable regularity dependent on the time of year, week or dayis reffered to as seasonality. This is different from regular cyclic trends, such as the rise and fall of stock prices, that re-occur regularly but don’t have a fixed period. An example of this might be temperature in weather data - very simply every summer the temp increases and every winter the temp subsequently decreases. 

* Seasonality can be viewed by simply plotting your dataset and viewing any seasonal patterns that might show.

## Trend 
Trend is a pattern in data that shows the movement of a series to relatively higher or lower values over a long period of time. Trend usually happens for some time and then disappears, it does not repeat. A trend could be:
1. Uptrend - Time Series Analysis shows a general pattern that is upward.
2. Downtrend - Time Series Analysis shows a general pattern that is downward.
3. Horizontal / Stationary Trend - If no pattern is observed then it's called a Horizontal or stationary trend.

* Trend in your data can be visualised by simply plotting the dataset. This will give you an indication as to what trend your data has!

## Prerequisites
* Data must be of two columns (X and y), first column (x) must be named 'Date' and hold datetime value while the second column (y)
must hold numeric data and user defines name of (y) column in template.
* When using template user must ensure that the correct imports have been installed and are ready to go.


## Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make
are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue
with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact
Alder Hey Data Science Team - datascientists@alderhey.nhs.uk

GitHub: AlderHey-Data-Science
**OR**
GitHub: Alder-Hey-Innovation-Centre

Project Link: [https://github.com/AlderHey-Data-Science/Forecasting/XGBoostTemplateFinal.ipynb](https://github.com/AlderHey-Data-Science/Forecasting)
