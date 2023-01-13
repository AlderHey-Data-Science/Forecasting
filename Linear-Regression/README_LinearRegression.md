<h3 align="center">Template for Time Series Regression using Linear Regression (OLS)</h3>

  <p align="center">
    User Guide & Spec for Time Series Template Using Linear Regression (OLS)
    <br />
    <a href="https://github.com/AlderHey-Data-Science/Forecasting"><strong>Explore the docs »</strong></a>
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

There are many great tutorials on time series regression out there, however the majority disregard the users end goals and many relay information across in a confusing and clustered way. This template helps to eliminate confusion and make running regression models easy for everyone!

Here's How:
* Your time should be focused on delivering results through the most accurate methods possible. As such this regression template uses Linear Regression (OLS) model to tackle time series regression.
* Users define number of steps to predict, number to train and so on giving the user full control of their predictions.
* Template runs model fast giving results efficiently and accurately!

Of course, no one time series regression template will serve all projects since your needs may be different. Note: A different model may be better suited to YOUR data!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With
* Python 
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
Firstly it is recommended users have a slight grasp of Python syntax to be able to follow along the script! This templae was created for Alder Hey Innovation Trust with the hope of using on patient data.

### Prerequisites

* Data must be of two columns (X and y), first column (x) must be named 'Date' and hold datetime value while the second column (y) must hold numeric data and user defines name of (y) column in template.
* When using template user must ensure that the following imports have been downloaded and are ready for use in Python evironment, these imports are; Panadas, NumPy, xgboost, sklearn, datetime, dateutil and statsmodels.


<!-- USAGE EXAMPLES -->
## Usage

The template has been designed with ease of use in mind. To use the template: 
* Firstly access the 'Load Data' section near the top of template and change the file location for the relevant data you wish to use.
* Once done execute and move to the 'User Defined' section just under 'Load Data'. Here the user is required to set the following paramters: 
* target_col = Name of users numeric (y) target column
* length_of_split = Depends on the time scale of your data E.g. 12 for monthly cycles.
* number_of_steps = The number of steps the user wants to predict E.g 7 day forecast (number_of_steps = 7).
* length_of_train = The number of values used for training the model.



<!-- ROADMAP -->
## Roadmap

- [ ] Finished template 1

See the open issues for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See LICENSE.txt for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Alder Hey Data Science Team - datascientists@alderhey.nhs.uk
GitHub: AlderHey-Data-Science
**OR**
GitHub: Alder-Hey-Innovation-Centre

Project Link: [https://github.com/AlderHey-Data-Science/Forecasting/Linear-Regression/linearRegressionTemplate.ipynb](https://github.com/AlderHey-Data-Science/Forecasting/Linear-Regression)

<p align="right">(<a href="#readme-top">back to top</a>)</p>










