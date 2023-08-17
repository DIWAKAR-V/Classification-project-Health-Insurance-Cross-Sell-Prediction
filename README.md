# Classification-project:Health Insurance Cross Sell Prediction

# **Business Context**
<br> Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.

An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.
Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer.

## **Project Execution:**

1.Understanding the dataset, performing some basic data inspection to verify the number of columns, comprehending data distribution, and examining the statistics 
  for each variable.

2.Performing Exploratory Data Analysis to get maximum insights from the raw dataset as well as visualising the data to make these insights easily understandable.

3.Data processing that includes taking care of missing values, outlier detection using box-plots and outlier removal using IQR and technique, multicolliniearity 
  detection.

4.Feature Engineering, which is creating new features, dropping the unnecessary ones, converting categprical features into numerical using Label encoding and 
   getting new features from a multi-label categorical feature using One Hot Encoding and finally Feature Selection before model building.

5.Defining model prerequisits such as Train-Test split, Feature transformation, Feature Scaling and setting hyperparameters.

6.Experimenting with various ML algorithms and getting their evaluation scores and feature importances.

7.We experimented using simple Random Forest Classifier,Gradient Boosting Classifier,Naive bayes classifier,knn neighbours classifier,XGBclassifier,Decision tree classifier. We employed Hyperparameter Tuning using HalvingRandomSearchCV on the tree based models.

8.We finally concluded the project with Random Forest Classifier giving the best model performance.

## **Project Conclusion and Inference:**

**We observed the following conclusions after executioning this project:**

1.Random Forest Classifier seems to be performing better as compared to other models. 

2.**previously_insured** is the most prominent feature as derived from ExtraTreeRegressor.

## **Model Performance description**

- **Random Forest Classifier** seems to be performing better as compared to other models and we can consider it to be the best model here for this problem statement.


- **Random Forest Classifier** gives us  **Roc Accuracy Score-97%**,**Accuracy Score-90%**.

