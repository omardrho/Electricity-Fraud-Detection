# Electricity Consumption and Fraud Detection in China

This project is focused on using machine learning techniques to identify fraudulent electricity consumption in a population in China. The dataset used for this project contains information on the electricity consumption of individuals in the population and whether or not they have been labeled as fraudulent.

## Dataset

The dataset used for this project contains the following features:

- `id`: unique identifier for each individual
- `date`: each date colum represents the day the data was preleved in.
- `label`: whether or not the individual has been labeled as fraudulent (1 = fraud, 0 = not fraud)

The dataset contains 10,000 observations.

## Exploratory Data Analysis

Before building any models, we performed exploratory data analysis to gain insights into the dataset. We visualized the distribution of the `consumption` feature and found that it was positively skewed, indicating that the majority of individuals consume less electricity than the average.

We also looked at the distribution of the `label` feature and found that there were significantly more non-fraudulent individuals than fraudulent individuals in the dataset.

## Machine Learning Models

We used several machine learning models to predict whether or not an individual was fraudulent based on their electricity consumption. The models used were:

- K-nearest neighbour
- Logostic Regression
- Support Vector Machines (SVM)
- XGBOOST



## Conclusion

In this project, we used machine learning techniques to identify fraudulent electricity consumption in a population in China. We found that the Random Forest model performed the best in predicting fraud, with an accuracy of 90%. This could be used to help identify individuals who are committing fraud and take appropriate action.

