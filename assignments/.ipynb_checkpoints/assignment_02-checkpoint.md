# Assignment 02 - Supervised Learning


## Description

Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming. Banks use machine learning to automate this process.

In this project, you will build a credit card approval predictor using supervised machine learning techniques discussed during the class.


## Data

The dataset used in this project is the [Credit Card Approval dataset](http://archive.ics.uci.edu/ml/datasets/credit+approval) from the UCI Machine Learning Repository.


## Solution

Your solution should have the following steps:

1- **Exploratory data analysis:** check columns to understand datatypes, value ranges, find possible missing values, the correlation between features, and create relevant data visualization

2- **Linear learner**: create an ML pipeline with a linear model. Explicitly mention your model assumptions and what you did to make sure those assumptions hold

3- **non-linear model**: also fit a non-linear model of your choice to compare the result

4- **ensemble model**: use any of the discussed ensemble methods to create a new model based on step 2 and 3

5- Use the model from step 4 to create a fucntion called `credit_approval` that takes a single row of data and predict if a credit card will be granted or not. It should looklike something like below.

```
def credit_approval(row, model):
   """
   Main function to take a sample data and use a trained model to predict if sample's application will get approved or not

   row: sample data
   model: ensemble model you have already trained
   """
   
   result = model.predict(row)
   
   return result

```


## Submission
Make sure your notebook as formatted, is commented and has enough written information for anyone to follow your process (use markdown cells). 
Similar to the previous assignment, follow the suggested folder structure.
