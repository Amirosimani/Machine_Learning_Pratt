# Assignment 04 - Neural Networks

## Description

This assignment has two sections. Each section has multiple parts with their respective point in parentheses. 

* First part is to build on what you have already done for **assignment 02**. Using the same `wine quality` data, build a neural net classifier with 2 dense hidden layers and report the classifier performance for the test set using confusion matrix (50%).
    - Don't forget preprocessing your data (scaling, encoding, and handling missing values)
    - Use 16 and 8 parameters parameters in your hidden layers. Use Adam optmizer without any dropout. Use ReLU for the hidden layers nad softmax for the output layer activation function. 
    - Double up the number of parameters while keeping everything else the same and compare the result. Explain the difference in the performance of your classifiers.

* The second part is to classify images using CNN. The dataset for this excersise is [food images](https://www.kaggle.com/kmader/food41) (50%). 
    - First, build a custom model with your choice of the parameters like layer size, number of convolution layer, filter size, etc.
    - Then, take advantage of `transfer learning` by picking `Inception Net`



[IMPORTANT]: Please note that based on the size of your model and your laptop configuration, each epoch might take a few hours to finish. It will be helpful to run all the steps from data processing to training on a small subset of the data first (100 images). Once you confirmed that your code works, then you can run using all of the data.  


## Submission
Make sure your notebook is formatted, commented, and has enough written information for anyone to follow your process (use markdown cells). Similar to the previous assignment, follow the suggested folder structure.


---
#### code of conduct

* Your answers to this assignment must be your own work.
* You may use Google, Stack OVerflow, etc but do not search for solutions to the overarching problem we're asking you to solve.
* You may not share your solutions with anyone else. This includes anything written by you, as well as any official solutions provided by Lazard.
* You may not engage in any other activities that will dishonestly improve your results or dishonestly improve or damage the results of others.
