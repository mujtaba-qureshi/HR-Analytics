# HR-Analytics
# ML - Supervised Learning
Creating a Supervised Learning Model for Predicting Employee Retention/Turnover

## Introduction
* The objective of this project is to create a _Supervised Learning Model_ which predicts employee retention based on certain HR metrics.
* The project will also explore the effects/benefits of preprocessing the data before using it to build/train an ML model

#### Link to the data
The data for this project was downloded from [Kaggle](https://www.kaggle.com/giripujar/hr-analytics)

## Walkthrough Steps
_Note:_ The data did not require any major cleaning

1. **Analysis**:
* Getting an overview of the distribution of metrics for people who stayed with the company vs people who left
* Determining the differences in metrics for the two sets of employees by running _confidence interval tests_
2. Fitting a **Log Regression Line** through the data (to interpret impact on individual metrics on employee retention)
3. **ML Modelling**
* Building a _Regression Model_ using **Unscaled Data**
* Building _Ensemble_ models using **Scaled Data**
4. Comparison of two Models

### Conclusion
A Random Forest Classifier was able to predict Employee Retention with **99%** accuracy once _Scaled Data_ was used to build it
