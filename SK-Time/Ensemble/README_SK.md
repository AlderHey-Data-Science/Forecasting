## Using Ensembling Forecaster from sktime library.

### Top 5 performing models in order are:
* AutoETS
* TBATS
* BATS
* SARIMAX
* Decision Tree

* When selecting top models to ensemble be wary of the algorithm approaches they use. For instance top 3 all use exponential smoothing hence why I've ensembled them 3 and then ensembled AutoETS, SARIMAX & Decision Tree as these models differ in approaches and cover a larger basis of errors.
* Note evaluation of the two models are attached to evaluation in sktime folder.
