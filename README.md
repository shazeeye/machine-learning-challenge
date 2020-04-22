# Machine Learning Homework - Exoplanet Exploration


## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, I used RandomForest to classify exoplanets from the raw dataset.

In this homework assignment, you will need to:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-RandomForestModel-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

- - -

## Instructions

### Preprocess the Data

* Preprocessed the dataset prior to fitting the model.
* Performed feature selection and remove unnecessary features.
* Used `MinMaxScaler` to scale the numerical data.
* Separated the data into training and testing data.

### Tune Model Parameters

* Used `GridSearch` to tune model parameters.
* Tuned and compare at least two different classifiers.

### Reporting

* Model is good enough to predict new exoplanets when you see the training and test scores.



| Score         |  Before Training  |  After training using GridSearch |
| ------------- |:-----------------:| --------------------------------:|
| Training Score| 0.9933244325767691| 1.0                              |
| Testing Score | 0.8787185354691075| 0.8993135011441648               |



