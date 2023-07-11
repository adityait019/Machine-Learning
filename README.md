# Rain Prediction in Australia using Classification Techniques

## Project Scenario

This project focuses on predicting whether there will be rain in Australia the following day. 
The dataset used for this project is obtained from the Australian Government's Bureau of Meteorology. 
The goal is to build a classifier that can accurately predict rain based on various weather attributes.

## Project Objectives

The objectives of this project are as follows:

1. Obtain and clean the rainfall dataset from the Australian Government's Bureau of Meteorology or an alternative reliable source.
2. Apply different classification algorithms to the cleaned dataset.
3. Evaluate the performance of each classifier using appropriate evaluation metrics.
4. Compare the results and identify the best-performing classifier for rain prediction.

## Dataset

You can obtain the rainfall dataset from the Australian Government's Bureau of Meteorology or choose an alternative reliable source.
The dataset should contain various weather attributes such as temperature, humidity, wind speed, and pressure, along with a target variable indicating
whether it rained the next day.
I have used data set `https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillUp/labs/ML-FinalAssignment/Weather_Data.csv`

## Classification Algorithms

The following classification algorithms will be applied to build the prediction models:

1. Linear Regression: This algorithm will be used to build a linear model to predict rain based on the input features.
2. K-Nearest Neighbors (KNN): KNN algorithm will be applied to classify the data points based on their proximity to the neighboring points.
3. Decision Trees: Decision tree algorithm will be used to create a tree-like model for rain prediction based on the feature conditions.
4. Logistic Regression: Logistic regression will be applied to estimate the probability of rain occurrence based on the input features.
5. Support Vector Machines (SVM): SVM algorithm will be used to find the hyperplane that best separates the rain and non-rain instances.

## Evaluation Metrics

The performance of each classifier will be evaluated using the following metrics, where applicable:

1. Accuracy Score: Measures the overall accuracy of the classifier in predicting rain.
2. Jaccard Index: Evaluates the similarity between the predicted and actual rain occurrences.
3. F1-Score: Represents the balance between precision and recall of the classifier.
4. LogLoss: Measures the performance of the classifier's predicted probabilities compared to the true probabilities.
5. Mean Absolute Error: Calculates the average absolute difference between the predicted and actual rain occurrences.
6. Mean Squared Error: Computes the average squared difference between the predicted and actual rain occurrences.
7. R2-Score: Measures the proportion of variance in the rain occurrences that can be explained by the classifier.

## Conclusion

This project aims to build a rain prediction classifier using various classification algorithms.
By applying these algorithms and evaluating their performance, you will gain insights into the effectiveness of each method in predicting rain in Australia. 
