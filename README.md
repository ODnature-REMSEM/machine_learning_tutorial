# Machine Learning Tutorial

This repository is meant to be an introduction to getting started with machine learning. Starting with some very basic concepts, you'll see that applying machine learning in itself can be very simple.


## Setup

The easiest way to get started is by using anaconda, and activating the supplied environment.

```
conda env create -f environment.yml
conda activate -n machine_learning_tutorial
```

This will install the required libraries and python version. If you prefer not to work with something like conda, you can also install the listed requirements separately.

## Notebooks

[`1_basic_regression.ipynb`](1_basic_regression.ipynb): Showcases a simple regression model.

[`2_basic_classification.ipynb`](2_basic_classification.ipynb): Showcases a simple classification model.

[`3_different_models.ipynb`](3_different_models.ipynb): Shows how different models can be used and compared.

[`4_preprocessing.ipynb`](4_preprocessing.ipynb): Goes over data preprocessing for machine learning.

[`5_sklearn_pipelines.ipynb`](5_sklearn_pipelines.ipynb): Shows how to integrate the preprocessing steps into your model.

[`6_hyperparameter_tuning.ipynb`](6_hyperparameter_tuning.ipynb): Shows how to tune the parameters of your model.

[`7_model_export.ipynb`](7_model_export.ipynb): Shows how to export your model as a file to be used in a different place.

[`8_explainability.ipynb`](8_explainability.ipynb): Shows how to make your model explainable and explain the influence of certain features.
