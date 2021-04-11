### Project 1. Credit risk default prediction: Project overview
This project was completed as part of [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk) competition hosted on Kaggle. The objective of this competition was to use data from various sources like credit bureau, previous loan applications, previous loan performance, previous credit card performance, installment payments and current application data in order to predict the probability of default of the applicant. The output of this model (in form of scores or risk bands) can then be used to make a credit decision (approve/reject) regarding the application. <br />
Currently the project consists of following parts: <br />
**Part 1:** Importing the raw training datasets, aggregate feature creation, & mapping these features on trainign data <br />
**Part 2:** EDA on training data with mapped features, baseline model (logistic regression), & tuning the model performance (by Feature engineering & feature selection)<br />
**Part 3 (Work in progress):** <br />
  1. Create credit bureau features using the bureau data provided and use them in the final model
  2. Try ensembling algorithms to see if it improves model performance any further

**Final Result**
| Model version | ROC score | Kaggle performance (on test data) |
| ------------- | ----------- | ----------------- |
| Logistic regression (baseline) | 0.6303 | 0.6109 |
| Logistic regression (After feature selection) | 0.7486 | 0.7351 | 
