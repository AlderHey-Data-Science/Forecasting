<h3 align="center">Template for Time Series Forecasting using sktime (Sci-Kit Time) library in Python</h3>

  <p align="center">
    User Guide & Spec for Time Series Template Using sktime Library 
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
        <li><a href="#about-sktime">About sktime</a></li>
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

This project aims to ease the process of forecasting on time series data through the exploration of Python's "sktime" library. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## About sktime library

* Sktime is a library for time series analysis in Python. It provides a unified interface for multiple time series learning tasks. 
* Currently, this includes time series classification, regression, clustering, annotation and forecasting. 
* It comes with time series algorithms and scikit-learn compatible tools to build, tune and validate time series models.


### Advantages of using SKTIME

* Sktime's main advantage is it's function to use many forecasting tools under one unified API.
* Sktime brings together functionalities from many forecasting libraries. 
* It allows users to easily implement, analyse and compare new models. It helps to avoid confusion in choosing an appropriate algorithm thanks to a clear classification of forecasters.
* It makes the workflow readable and understandable as all forecasters share a common interface. They are implemented in separate classes, as in other toolboxes, including scikit-learn. 
* It enables altering forecasters in a workflow. This saves us from adjusting the structure of our code each time we change our model.
<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With
* Python 
* Jupyter Notebooks
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
Firstly it is recommended users have a slight grasp of Python syntax! This templae was created for Alder Hey Innovation Trust with the hope of improving the accuracy of regression models by exploring different approaches.

### Prerequisites

* For this template data must be of two columns (X and y), first column (x) must be named 'Date' and hold datetime value while the second column (y) must hold numeric data and user defines name of (y) column in template.
* At end of script an example of multivariate forecasting is shown!
* When using template user must ensure that the following imports have been downloaded and are ready for use in Python evironment, these imports are found on sktime script.


<!-- USAGE EXAMPLES -->
## Usage

The template has been designed with ease of use in mind. To use the template: 
* Firstly access the 'Load Data' section near the top of template and change the file location for the relevant data you wish to use.
* Once done execute and move to the 'User Defined' section just under 'Load Data'. Here the user is required to set the following paramter: 
* target_col = Name of users numeric (y) target column.

* After user must define size of test and train for Y target column 
* This length is then used to define forecast horizon (length to forecast).
* After which models can be called and results obtained making evaluating between models simple and easy to follow along with.





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

Project Link: [https://github.com/AlderHey-Data-Science/Forecasting](https://github.com/AlderHey-Data-Science/Forecasting)

<p align="right">(<a href="#readme-top">back to top</a>)</p>