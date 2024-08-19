# HR_DataAnalysis

**Project Overview**
This project involves predicting employee attrition using an HR dataset with an initial size of 14,999 records. After removing 3,008 duplicate entries, the refined dataset contains 11,991 unique records. The objective was to evaluate different machine learning models and identify the most effective approach for predicting employee turnover.

**Data**
The dataset, HR_Dataset.csv, includes features such as satisfaction level, last evaluation, number of projects, average monthly hours, time spent in the company, work accident, promotion in the last 5 years, departments, and salary.

**Steps**
**1.Data Exploration & Cleaning:**

* Loaded and explored the dataset.
* Removed duplicate records and handled missing values.
* Renamed columns for consistency.
  
**2.Preprocessing:**

* Applied Standard Scaling to numerical features.
* Used One-Hot Encoding for categorical features (departments).
* Employed Ordinal Encoding for ordinal features (salary).
  
**3.Modeling:**

* Created a pipeline combining preprocessing and model training.
* Evaluated several models:
      Logistic Regression
      Decision Tree Classifier
      Random Forest Classifier
      XGBoost Classifier
      LightGBM Classifier
**4.Performance Evaluation:**

* Metrics used: Accuracy, Precision, and Recall.
* Results:
Model	Accuracy	Precision	Recall
Logistic Regression	83.7%	52.1%	21.9%
Decision Tree	97.0%	89.9%	92.2%
Random Forest	98.6%	98.9%	92.7%
XGBoost	98.4%	96.9%	93.2%
LightGBM	98.4%	97.1%	92.9%

**Requirements**
* Python
* pandas
* numpy
* scikit-learn
* lightgbm
* xgboost

