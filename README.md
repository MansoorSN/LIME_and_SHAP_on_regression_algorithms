# LIME_and_SHAP_on_regression_algorithms
In this repo I will use the Support Vector Regression(SVR) to predict the prices of the Airbnb listings in major cities. The SVR model is further explained using SHAP and LIME.

The dataset used in this notebook is a preprocessed dataset from the [AirBnB listings in major US cities](https://www.kaggle.com/rudymizrahi/airbnb-listings-in-major-us-cities-deloitte-ml/kernels) dataset.

To learn more about the LIME refer the paper: ["Why Should I Trust You?": Explaining the Predictions of Any Classifier](https://arxiv.org/abs/1602.04938) and [github repo](https://github.com/marcotcr/lime).

To learn more about the SHAP refer the paper:[A Unified Approach to Interpreting Model Predictions](https://arxiv.org/abs/1705.07874) and [github code implementation](https://github.com/slundberg/shap)

Note: the target variable i.e the rental price of a property is a normalized value with mean=0.

The SHAP output value is:
![SHAP output](https://raw.githubusercontent.com/MansoorSN/LIME_and_SHAP_on_regression_algorithms/main/SHAP%20output.png)

The  output LIME output value is:
![LIME output](https://raw.githubusercontent.com/MansoorSN/LIME_and_SHAP_on_regression_algorithms/main/LIME%20output.png)
