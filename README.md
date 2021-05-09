## [Project 1. Credit risk default prediction: Project overview](https://github.com/vinayakn87/Credit-risk-default-prediction)
ML model to predict the probability of default of the applicant using data from various sources like credit bureau, previous loan applications, previous loan performance, previous credit card performance, installment payments and current application. Data for the project comes from [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk) competition hosted on Kaggle.
Currently the project consists of following parts: <br />
**Part 1:** Importing the raw training datasets, aggregate feature creation, & mapping these features on trainign data <br />
**Part 2:** EDA on training data with mapped features, baseline model (logistic regression), & tuning the model performance (by Feature engineering & feature selection)<br />
**Part 3 (Work in progress):** Try ensembling algorithms to see if it improves model performance any further

**Result & Outcomes:**<br />
Current best model => Logistic regression with ROC 0.7486 on train & Kaggle score 0.7351 (on test)

## [Project 2. Credit card fraud detection](https://github.com/vinayakn87/Credit-card-fraud-detection)
The objective of this project was to build a machine learning model to detect fraudulent credit card transactions from given data. The Kaggle dataset used in this notebook can be found [here](https://www.kaggle.com/mlg-ulb/creditcardfraud). We approach this problem from two perspectives, first trying to use tradiotional ML models which minimize misclassification ignoring the costs and second by trying to minimize the cost while allowing higher missclassfication.
Following three methods have been illustrated to explore this:
1. Traditional ML models which try to which minimize misclassification
2. Cost sensitive classification using Bayes minimum risk classifier
3. Threshold optimization to minimize costs

**Result & Outcomes:**<br />
![text here](https://github.com/vinayakn87/Portfolio/blob/master/images/Capture.JPG)


