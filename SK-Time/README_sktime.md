<h3 align="center">Template for Time Series Regression using SKTIME (Python package)</h3>

  <p align="center">
    User Guide & Spec for Time Series Template Using SKTIME
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
      <a href="#about-the-project">What is SKTIME?</a>
      <ul>
        <li><a href="#advantages-of-using-sktime">Advantages of Using sktime</a></li>
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



<!-- What is SKTIME? -->
## What is SKTIME?
Sktime is an open-source toolbox for time series modelling. It combines functionalities spread across many Python libraries. It also adds its own unique features for forecasting. It allows for the training, fine-tuning and evaluation of models for time series. It is compatible with scikit-learn. The framework also enables, time series classification, feature extraction and time series clustering.

### Advantages of using SKTIME
* Sktime's main advantage is it's function to use many forecasting tools under one unified API.
* Sktime brings together functionalities from many forecasting libraries. 
* It allows users to easily implement, analyse and compare new models. It helps to avoid confusion in choosing an appropriate algorithm thanks to a clear classification of forecasters.
* It makes the workflow readable and understandable as all forecasters share a common interface. They are implemented in separate classes, as in other toolboxes, including scikit-learn. 
* It enables altering forecasters in a workflow. This saves us from adjusting the structure of our code each time we change our model.


### Built With
* Python (sktime package)
* Jupyter Notebooks


<!-- GETTING STARTED -->
## Getting Started
Firstly it is recommended users have a slight grasp of Python syntax! This templae was created for Alder Hey Innovation Trust with the hope of improving the accuracy of regression models by exploring different approaches.

### Prerequisites

* This template explores sktime's functionality on univariate data sets.
* Note - XGBoost, Prophet and Linear Regression models within template have been added but are resulting in poorer performance when compared to these models isolated from sktime.
* XGBoost isolated model link - [https://github.com/AlderHey-Data-Science/Forecasting/Tree/main/XGBoost/XGBoostTemplateFinal.ipynb](https://github.com/AlderHey-Data-Science/Forecasting/Tree/main/XGBoost/XGBoostTemplateFinal.ipynb)
* Prophet isolated model link - [https://github.com/AlderHey-Data-Science/Forecasting/Tree/main/Prophet/prophetRegressionTemplateFinal.ipynb](https://github.com/AlderHey-Data-Science/Forecasting/Tree/main/Prophet/prophetTemplateFinal.ipynb)
* Linear Regression isolated model link - [https://github.com/AlderHey-Data-Science/Forecasting/Tree/main/Linear-Regression/linearRegressionTemplate.ipynb](https://github.com/AlderHey-Data-Science/Forecasting/Tree/main/Linear-Regression/linearRegressionTemplateFinal.ipynb)


<!-- USAGE EXAMPLES -->
## Usage

The template has been designed with ease of use in mind. To use the template: 
* Firstly access the 'Load Data' section near the top of template and change the file location for the relevant data you wish to use.
* Once done set your forecasting horizon and run the program.
* Bottom of script outputs all models and MAE (Mean Absolute Error) score evaluating all models on your data so you know what fits best!


<!-- ROADMAP -->
## Roadmap

- [ ] Finished template 1

See the open issues for a full list of proposed features (and known issues).

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





<!-- LICENSE -->
## License

Distributed under the MIT License. See LICENSE.txt for more information.

<!-- CONTACT -->
## Contact

Alder Hey Data Science Team - datascientists@alderhey.nhs.uk
GitHub: AlderHey-Data-Science
**OR**
GitHub: Alder-Hey-Innovation-Centre

