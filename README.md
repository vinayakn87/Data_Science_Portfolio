## Project 1. Credit risk default prediction: Project overview
ML model to predict the probability of default of the applicant using data from various sources like credit bureau, previous loan applications, previous loan performance, previous credit card performance, installment payments and current application. Data for the prject comes from [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk) competition hosted on Kaggle.
Currently the project consists of following parts: <br />
**Part 1:** Importing the raw training datasets, aggregate feature creation, & mapping these features on trainign data <br />
**Part 2:** EDA on training data with mapped features, baseline model (logistic regression), & tuning the model performance (by Feature engineering & feature selection)<br />
**Part 3 (Work in progress):** Try ensembling algorithms to see if it improves model performance any further

**Final Result**
| Model version | ROC score | Kaggle performance (on test data) |
| ------------- | ----------- | ----------------- |
| Logistic regression (baseline) | 0.6303 | 0.6109 |
| Logistic regression (After feature selection) | 0.7486 | 0.7351 | 
