# Project 1 Instructions

## Overview

For this exercise, you will be creating a logistic regression model on the `project1_data.csv` file. Below are a series of steps, you are to create a notebook which accomplish the steps. You will turn in a .pdf file which shows your notebook along with the cell output. Focus not just on correctness, but also on legibility. Correct answers that are too convoluted for the grader to understand will not recieve full credit - remember that code is not just run, it is also read by others.

Good machine learning practitioners are autonomous and proactive. In particular, they should not need to be told what the steps are in the problem solving process. In future projects, full steps will not be given as they are below. Instead it might be something closer to: "fit a logistic regression model to the data."

## Expectations

This project is to be completed independently from each other, but not from the internet. This means you should not consult fellow students in completing it, but you may consult internet resources like standard documentation and stackoverflow.

## Project directions

Please complete the following steps, showing your work along the way. Read all steps before beginning work as later tasks will inform how you might approach earlier tasks.

1. Import the `project1_data.csv` file as a pandas dataframe. (5 points)
2. Identify any nulls in the data and either impute or remove as appropriate. Include your reasoning. (10 points)
3. Identify any erroneous data and either impute or remove as appropriate. Include your reasoning. (10 points)
4. Split the data into a train (80%) and test (20%) set. (5 points)
5. Perform exploratory data analysis. Write down your single most interesting observation about the data with justification. (10 points)
6. Appropriately encode the categorical feature variables. (10 points)
7. Encode the target column (y) as 0 (no) and 1 (yes). (5 points)
8. Calculate the prevalence (class balance) of the target. (5 points)
9. Fit a logistic regression model on the training set. (5 points)
10. Use your model to generate probability predictions on the test set. (5 points)
11. Calcuate the area under the ROC curve of your predictions on the test set. (5 points)
12. Choose an appropriate decision threshold and create class predictions for your model on the test set. (5 points)
13. Produce a confusion matrix for your class predictions. (5 points)
14. Write a short summary of the data including its quality and appropriateness for modeling y. Comment on the quality of your model and give a recommendation to a business stakeholder regarding the potential value of its use. (15 points)

