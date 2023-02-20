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
