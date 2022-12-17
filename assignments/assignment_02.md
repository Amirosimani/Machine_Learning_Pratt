# Assignment 02 - Supervised Learning


## Description

Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming. Banks use machine learning to automate this process.

In this project, you will build a **red wine quality classifier** using supervised machine learning techniques discussed during the class.


## Data

The dataset used in this project is the [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) from the UCI Machine Learning Repository.


## Solution

Your solution should have the following steps:

1. **Exploratory data analysis:** check columns to understand datatypes, value ranges, find possible missing values, the correlation between features, and create relevant data visualization
2.  **Modeling**:
   * create a sklearn pipeline  that includes preprocessing steps such as scaling and one hot encoding of categorical variable.
   *  train a **Linear learner** (like logistic regression) classfier and report the performance using confusion matrix
   *  train a**non-linear classifer** (like random forrest) and report the performance using confusion matrix.
3. **Hyperparameter Tuning**: Pick the model with the highest F1 score and run agrid search to improve the result. Report the best set of parameters.

4. Use the best model from step 3 to create a function that takes a single row of test data and predict the quality of wine. It should looklike something like below.

```
def wine_quality(row, model):
   """
   Main function to take a sample data and use a trained model to predict wine quality

   row: sample data
   model: ensemble model you have already trained
   """
   
   result = model.predict(row)
   
   return result

```


## Submission
Make sure your notebook as formatted, is commented and has enough written information for anyone to follow your process (use markdown cells). 
Similar to the previous assignment, follow the suggested folder structure.
