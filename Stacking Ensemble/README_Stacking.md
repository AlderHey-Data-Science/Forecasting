<h3 align="center">Stacking Ensemble Example</h3>

  <p align="center">
    User Guide & Spec for Ensembling Algorithms Through Stacking Technique
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
      <a href="#about-the-project">What is Stacking?</a>
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- What is Darts? -->
## What is Stacking?

* In short, ‘Stacking’ is an ensemble machine learning algorithm that involves combing the predictions from multiple machine learning models on the same dataset, like bagging and boosting. 
* Stacking helps to address the question: Given multiple machine learning models that are trusted on a problem, but in different ways, how do you choose which model to use?
* The approach to this question is to use another machine learning model that learns when to use or trust each model in the ensemble. 
* Unlike bagging, in stacking, the models are typically different (e.g., not all decision trees) and fit on the same dataset (e.g., instead of samples of the training dataset).
* Unlike boosting, in stacking, a single model is used to learn how to best combine the predictions from the contributing models (e.g., instead of a sequence of models that correct the predictions of prior models).

### Architecture of Stacking
* The architecture of a stacking model involves two or more base models, often referred to as level-0 models, and a meta-model that combines the predictions of the base models, referred to as a level-1 model.
* Level-0 Models (Base-Models): Models fit on training and predictions are compiled.
* Level-1 Model (Meta-Model): Model that learns how to best combine the predictions of the base models.
* The meta-model is trained on the predictions made by base models on out-of-sample data. That is, data not used to train the base models is fed to the base models, predictions are made, and these predictions, along with the expected outputs, provide the input and output pairs of the training dataset used to fit the meta-model.

### Notes

* Stacking is designed to improve modelling performance, although is not guaranteed to result in an improvement in all cases.
* If a base-model performs as well as or better than the stacking ensemble, the base model should be used instead, given its lower complexity (e.g., its simpler to describe, train and maintain).


<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With
* Python (Darts package)
* Jupyter Notebooks
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
Firstly it is recommended users have a slight grasp of Python syntax! This templae was created for Alder Hey Innovation Trust with the hope of improving the accuracy of regression models by exploring different approaches.

### Prerequisites

* This template explores ensembling forecasting models through Stacking on univariate data sets.

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