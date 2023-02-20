<h3 align="center">Template for Time Series Forecasting using AutoTS (Automated Time Series) Python Library.</h3>

  <p align="center">
    User Guide & Spec for Time Series Template Using AutoTS
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
      <a href="#about-the-project">What is AutoTS?</a>
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



<!-- What is AutoTS? -->
## What is AutoTS?

* AutoTS is a time series library for Python designed for rapidly deploying high-accuracy forecasts at scale.
* There are dozens of forecasting models usable in the sklearn style of .fit() and .predict(). These include naïve, statistical, machine learning, and deep learning models.
* All models support forecasting multivariate (multiple time series) and univariate outputs and support probabilistic (upper/lower bound) forecasts. 


### Advantages of using AutoTS

* Automatically builds tens to hundreds of different variation models for algorithms specified by the user and includes ensemble models of these displayed with metric calculations, what model it’s for, the parameters for that model, the run time and an overall score in an easy-to-read table format once read to excel/csv.
* Easiest library to use out of the three, simply call-in data, process into specified format, perform split for training and testing, specify models to use then build AutoTS model and fit on training data. Once run, you can print best model and output evaluation to excel/csv for further analysis.
* AutoTS automatically builds ensembles of different parameters from the models in which you define in the script.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With
* Python (sktime package)
* Jupyter Notebooks
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
Firstly it is recommended users have a slight grasp of Python syntax! This templae was created for Alder Hey Innovation Trust with the hope of improving the accuracy of regression models by exploring different approaches.

### Prerequisites

* This template explores AutoTS functionality on univariate data sets.


<!-- USAGE EXAMPLES -->
## Usage

The template has been designed with ease of use in mind. To use the template: 
* Firstly access the 'Load Data' section near the top of template and change the file location for the relevant data you wish to use.
* After define your split for training and testing and define any models you want built by AutoTS.
* Now it's time to build the model calling AutoTS() then fit and watch this library try tens to hundreds of combinations using the models provided by the user.
* This evaluation is printed to excel where we can further evaluate based on a number of things including runtime, MAE and a list parameters. 


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

Project Link: [https://github.com/AlderHey-Data-Science/Forecasting/Tree/main/SK-Time](https://github.com/AlderHey-Data-Science/Forecasting/Tree/main/SK-Time)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
