# classification-challenge
AI camp module 13 challenge

## Background: 
Let's say you work at an Internet Service Provider (ISP) and you've been tasked with improving the email filtering system for its customers. You've been provided with a dataset that contains information about emails, with two possible classifications: spam and not spam. The ISP wants you to take this dataset and develop a supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of its customers' inboxes.

You will be creating two classification models to fit the provided data, and evaluate which model is more accurate at detecting spam. The models you'll create will be a logistic regression model and a random forest model.

## Predict Model Performance

You will be creating and comparing two models on this data: a Logistic Regression, and a Random Forests Classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct! 

Write down your prediction in the designated cells in your Jupyter Notebook, and provide justification for your educated guess.

    Student Prediction: Initial prediction is that Random Forests Classifier will likely be more performant in this example. Previous class exercises and basic research leads me to believe that this model will provide a better prediction with this type of data. 

## Create and Fit a Logistic Regression Model
Calculate the accuracy score by evaluating y_test` vs. `testing_predictions`.

*Accuracy Score Logistic Regression: 0.928*

## Create and Fit a Random Forest Classifier Model
Calculate the accuracy score by evaluating y_test` vs. `testing_predictions`.

*Accuracy Score Radom Forest Classifier: 0.967*

## Evaluate the Models

Which model performed better? How does that compare to your prediction? Write down your results and thoughts in the following markdown cell.

*The Random Forest Classifier performed better compared to the Logistic Regression Model with the score being slightly higher with testing data. My original prediction ended up being accurate and supported by the results show in this workbook*