# Machine Learning Project Practice 

This project follows the structure and contents from Chapter 2 of the book *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow* by Aurélien Géron

# Learning Points from this Chapter 🌟

## Root Mean Square Error (RMSE)
RMSE is a performance measure, it is calculated by :
- taking the predicted value for instance x(i), minus the label for that instance

- square the outcome of above

- taking the sum of all the square differences for all instances 

- Take the average 

- Take Square Root 

## Pearson's r
The standard correlation coefficient, which often refers to the Pearson correlation coefficient (r) can be used to measure the linear relationship between two numerical quantities

## Transformations and Pipelines 
Transformation means to change data from one form to another 
Pipeline is a sequence of transformations

## Feature Scaling
Models don't perform well on features that have very different ranges, therefore it matters to scale the data to similiar ranges, two common ways include:

Min-max scaling : take the value minus mean, divide the result by max - min

Standardisation; take the value minus mean, sivide by standard deviation 


## Encoding
Models (at least some classical models) don't work well with non-numeric attributes 
so we need to change text attributes to be in terms of numbers

two common ways include: 

Ordinal Encoder: by alphabetical in default, or customised rank, give each attribute a unique integer 

One-hot encoding: make dummy attributes of non-*that attribute*
