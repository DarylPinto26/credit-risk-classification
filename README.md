# credit-risk-classification

## Overview of the Analysis

* The objective of this analysis is to analyze a dataset that portrays lending activities from a service that provides said loans. The analysis should predict the risk of providing loans to borrowers.
* The Financial information information avvailable in the dataset include -
  > loan size
  >
  > interest rate
  >
  > borrower income
  >
  > debt-to-income ration
  >
  > number of accounts
  >
  > derogatory marks
  >
  > total debt of each applicant
  >
  > loan status
  
* The dataset shows that there were  75036 healthy loan counts vs 2500 high-risk loan counts.

* Following are the stages of ML process for the analysis -
  > Pre-processing the data by cleaning raw data to prep for the model
  >
  > Splitting the data using the train-test split into training and testing datasets
  >
  > Fitting a logistic regression model by using the training data
  >
  > Evaluate the model’s performance
  >
  > Utilizing the RandomOverSampler module from the imbalanced-learn library to resample the data.
  >
  > Utilizing the LogisticRegression classifier and the resampled data to fit the model and make predictions
  >
  > Evaluate the model’s performance

## Results

* Machine Learning Model 1:
  * Accuracy - True positives = 18663, True negatives = 563
  * Precision - Healthy loans = 100%, High-Risk loans = 85% - (it describes how many predictions does the model make from the total number of datapoints in the dataset variable)
  * Recall - Healthy loans = 99%, High-Risk loans = 91% - (the percentage of recall describes how many correct predictions out of the precision percetage does the model make)



* Machine Learning Model 2:
  * Accuracy - True positives = 18649, True negatives = 615
  * Precision - Healthy loans = 100%, High-Risk loans = 84%
  * Recall - Healthy loans = 99%, High-Risk loans = 99%

## Summary

In my opinion, the second model makes more sense to use, since the recall percentage is way higher when compared to model 1, making predictions and its accuracy much more reliable in comparison. The first model is no doubt competent in its own right, however when compared with model 2, Model 2 is a better fit(atleast for the high-risk loans variable)
