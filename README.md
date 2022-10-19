# Project Name  Telecom Churn Case Study
> Outline a brief description of your project.
    You have a telecom firm which has collected data of all its customers. The main types of attributes are:

Demographics (age, gender etc.)

Services availed (internet packs purchased, special offers taken etc.)

Expenses (amount of recharge done per month etc.)

Based on all this past information, you want to build a model which will predict whether a particular customer will churn or not, i.e. whether they will switch to a different service provider or not. So the variable of interest, i.e. the target variable here is 'Churn' which will tell us whether or not a particular customer has churned. It is a binary variable - 1 means that the customer has churned and 0 means the customer has not churned.


## Table of Contents
* [General Info](#general-information) 
 The telecom company wants to understand the factors on which the churn depends. Essentially, it wants to know:

Which variables are significant in predicting the churning of customers so that it can take necessary action to retain customers in their company.
* [Technologies Used](#technologies-used) numpy,pandas,matplotlib,seaborn,sklearn,statsmodel
* [Conclusions](#conclusions) 
        Sensitivity is approx 86% in train dataset where as it is nearly 85% in unseen data which is prety good at 0.2 cutoff point.
* [Acknowledgements](#acknowledgements) Logistic Regression Model is used.

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
        You have a telecom firm which has collected data of all its customers.
- What is the background of your project?
        Based on all this past information, you want to build a model which will predict whether a particular customer will churn or not, i.e. whether they will switch to a different service provider or not. So the variable of interest, i.e. the target variable here is 'Churn' which will tell us whether or not a particular customer has churned. It is a binary variable - 1 means that the customer has churned and 0 means the customer has not churned.
- What is the business probem that your project is trying to solve?
        To create a logistic regression model that quantitatively relates churn probability.
- What is the dataset that is being used?
       1. "churn_data.csv"
       2. "customer_data.csv"
       3. "internet_data.csv"


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis   At 0.2 probability 69.5% ,85.7%,63.7% are the accuracy,sensitivity and specificity values respectively.
- Conclusion 2 from the analysis   AUC is 83%
- Conclusion 3 from the analysis   Out of 23 variables 8 variables are affecting the Churns.
- Conclusion 4 from the analysis   Logistic model is used which has done a decent job for our prediction. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - numpy
- library - pandas
- library - sklearn,statsmodel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on Upgrad


## Contact
Created by [@githubSanghamitraa] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->