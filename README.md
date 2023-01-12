# Forecasting Time Series Templates



## Project Description
This project aims to address univariate time series regression through the use of different algorithms such as XGBoost,
ARIMA, Prophet and Linear Regression. These models will be in template format allowing the users of these templates to
load in their relevant data, define specific variables meeting the needs of their data and get predictions for their target 
variable automatially output to csv. Users should be able to define the number of steps to predict, the length of train, 
the length of split and their target column. Once defined the program should run giving the user a mean absolute error value
used to evaluate the models performance based on the data the user has fed into the script.

## Time Series
Simply put time series data is data that is measured across a certain time scale, for example, seconds, minutes, hours, days, weeks,
months, years and so on. 

## XGBoost Vs. ARIMA Template
Specific README for XGBoost Vs. ARIMA Template has been uploaded and contains details specific to these models. Please check out 
XGBoost Vs. ARIMA Template for user guide and specification detailing more information.

## Prerequisites
* Data must be of two columns (X and y), first column (x) must be named 'Date' and hold datetime value while the second column (y)
must hold numeric data and user defines name of (y) column in template.
* When using template user must ensure that the following imports have been downloaded and are ready for use in Python evironment,
these imports are; Panadas, NumPy, xgboost, sklearn, datetime, dateutil and statsmodels.

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
