# Assignment 02 - Supervised Learning


## Description

In this project, you will build a **red wine quality classifier** using supervised machine learning techniques discussed during the class.


## Data

The dataset used in this project is the [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) from the UCI Machine Learning Repository.


## Solution

Your solution should have the following steps:

1. **Exploratory data analysis:** check columns to understand datatypes, value ranges, find possible missing values, the correlation between features, distribution of target values, and create relevant data visualization.
2.  **Modeling**:
    * create a sklearn pipeline  that includes preprocessing steps such as scaling and one hot encoding of categorical variable.
    *  train a **Linear learner** (like logistic regression) classfier and report the performance using confusion matrix. Describe what the result in the confusion matrix.
    *  train a**non-linear classifer** (like random forrest) and report the performance using confusion matrix. 
       Compare the result between the linear and non-linear model and explain the difference in their performance.
3. **Hyperparameter Tuning**: Pick the model with the highest **weighted average F1 score** and run a grid search to improve the result (using confusion matrix). Report back the best set of parameters.

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
