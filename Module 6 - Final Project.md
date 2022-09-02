## Module Introduction

The final module of this course is a project to determine which basketball teams are most likely to make it to the semifinal round of the College Basketball Tournament known as the Final Four.

You will have access to historical data and will apply different classification algorithms to accomplish this.

## Objective(s)

At the end of this lab, you will be able to:
* Apply ML to a dataset to make inferences

## Instructions

Now that you have been equipped with the skills to use different Machine Learning algorithms, you will have the opportunity to practice and apply it on a data set.

In this scenario, you are a Data Scientist working for a college basketball team. Your coaches have asked you to look at historical data to see which team metrics (individually or in combination) make a team more likely to make it into the Final Four. For example, if a team is more efficient defensively, does this have a direct relationship to their ability to get into the Final Four? What about defensively efficiency along with overall wins? Your job is to figure out if there is a combination of metrics that give a team more of a chance of making it into this tournament.

Something to keep in mind is that when trying to predict results of basketball tournaments there are many variables that need to be taken into account. As a result of this creating accurate models is incredibly hard. In the sports betting industry an accuracy rate of anything over 55% is considered good as it indicates profits.

You will load a historical data set from previous seasons, clean the data, and apply different classification algorithms to the data. You are expected to use the following algorithms to build your models:

* k-Nearest Neighbour
* Decision Tree
* Support Vector Machine
* Logistic Regression

The results are reported as the accuracy of each classifier, using the following metrics when applicable:

* Jaccard index
* F1-score
* Accuracy

## Review Criteria

**This final project will be graded by your peers who are also completing the course during the same session. This project is worth 25 marks of your total grade, and is distributed as follows:

1. Build a KNN model using a value of k equals five, find the accuracy on the validation data **(1 mark)**

2. Determine the accuracy for the first 15 values of k the on the validation data:. **(1 mark)**

Determine the minimum value for the parameter that improves results on validation data. (1 marks)

Building model using Support Vector Machine. (2 marks)

Train a logistic regression model and determine the accuracy of the validation data (set C=0.01) (2 marks)

Calculate the F1 score and Jaccard Similarity score for each model from above. Use the Hyperparameter that performed best on the validation data (2 marks)
