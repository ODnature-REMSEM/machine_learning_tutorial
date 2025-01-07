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

[`01_basic_regression.ipynb`](01_basic_regression.ipynb): Showcases a simple regression model.

[`02_basic_classification.ipynb`](02_basic_classification.ipynb): Showcases a simple classification model.

[`03_different_models.ipynb`](03_different_models.ipynb): Shows how different models can be used and compared.

[`04_preprocessing.ipynb`](04_preprocessing.ipynb): Goes over data preprocessing for machine learning.

[`05_sklearn_pipelines.ipynb`](05_sklearn_pipelines.ipynb): Shows how to integrate the preprocessing steps into your model.

[`06_hyperparameter_tuning.ipynb`](06_hyperparameter_tuning.ipynb): Shows how to tune the parameters of your model.

[`07_model_export.ipynb`](07_model_export.ipynb): Shows how to export your model as a file to be used in a different place.

[`08_explainability.ipynb`](08_explainability.ipynb): Shows how to make your model explainable and explain the influence of certain features.

[`09_geospatial_machine_learning.ipynb`](09_geospatial_machine_learning.ipynb): Shows how you can apply machine learning to geospatial data.

[`10_geospatial_data_splitting.ipynb`](10_geospatial_data_splitting.ipynb): Goes over the possible sources of data leakage, and how to prevent this in geospatial data.

[`11_computer_vision.ipynb`](11_computer_vision.ipynb): Goes over basic concepts of computer vision, and shows how to implement a model from scratch, or pretrained.
