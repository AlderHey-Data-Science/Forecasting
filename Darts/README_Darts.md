<h3 align="center">Template for Time Series Forecasting using Darts () Python Library.</h3>

  <p align="center">
    User Guide & Spec for Time Series Template Using Darts
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
      <a href="#about-the-project">What is Darts?</a>
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



<!-- What is Darts? -->
## What is Darts?

* Darts is a Python library for user-friendly forecasting and anomaly detection on time series. Contains a variety of models, from classics such as ARIMA to deep neural networks.
* Forecasting models can be used in the same way, using fit() and predict() functions, similar to scikit-learn.
* Darts makes it easy to back test models, combine the predictions of several models, and take external data into account.



### Advantages of using Darts

* Easy to ensemble top performing algorithms.
* Combination of models in a single library helps eliminate the annoyance of installing packages separately.
* Darts unlike others offers a test to check for seasonality.
* Easy to plot and score models based on a number of metrics from RMSLE to runtime.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With
* Python (Darts package)
* Jupyter Notebooks
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
Firstly it is recommended users have a slight grasp of Python syntax! This templae was created for Alder Hey Innovation Trust with the hope of improving the accuracy of regression models by exploring different approaches.

### Prerequisites

* This template explores Darts functionality on univariate data sets.


<!-- USAGE EXAMPLES -->
## Usage

The template has been designed with ease of use in mind. To use the template: 
* Firstly access the 'Load Data' section near the top of template and change the file location for the relevant data you wish to use.
* As you'll notice we import TimeSeries from darts library and store our data as a TimeSeries.
* After define your split for training and testing.
* Now it's time to build the models - Import these models from 'darts.models'.
* Once models have been initialised run the script then access the evaluation section (bottom of script) which lists scores for each model. The lower the score 
the better the fit!


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