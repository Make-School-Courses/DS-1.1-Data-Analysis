# Confidence Intervals & Outliers

### Min-by-Min Plan

- 10 min - What is confidence interval, and why is it important to learn?
- 5 min - Objectives
- 10 min - Review of Z distribution and significant level
- 10 min - Activity: Obtain the confidence interval for mean of sepal length for Iris dataset
- 25 min - TT: what is outlier?
- 10 min - Activity: find and remove outliers if our dataset is Normal
- 25 min - TT: outlier by Interquartile range (IQR) method
- 10 min - Activity: IQR outlier detection and removal
- 5 min - Q&A Wrap Up

## What is confidence interval? (10 min)

It is useful to estimate an interval for the possible values of the parameter and put a probability on how confident we are that the true parameter value falls inside this interval


## Learning Objectives (Competencies) (5 min)
By the end of this lesson, students will be able to:
1. Describe confidence interval and when and how apply to a sample data
2. Describe what is outlier and how to remove outlier for univariate data
3. Visualize the outliers by boxplot

## Activity: Obtain the confidence interval for mean of sepal length for Iris dataset (10 min)

Tasks:

1- Explore Iris dataset. How many features, records and plants does it have?
2- Gather all of the sepal length for Iris-setosa
3- Write a function that calculate lower and upper bound for mean of sepal length for Iris-setosa with %95 confidence.


## What is outlier? (5 min)

Outliers are extreme values that can skew our dataset, sometimes giving us an incorrect picture of how things actually are in our dataset. The hardest part of this is determining which data points are acceptable, and which ones constitute "outlier" status.


## Activity: find and remove outliers if our dataset is Normal

Task: Write a function that first find outliers for a normally distributed data, then remove them.


## Break (10 min)

## Interquartile range (IQR) for finding and removing outlier when data has any distribution (10 min)

Tukey suggested to calculate the range between the first quartile (25%) and third quartile (75%) in the data, called the interquartile range (IQR).

## Activity: IQR outlier detection and removal

Task: Write a function to find and remove outliers based on IQR method for a given data sample



## Review Answers of Challenges (10 min)

## Q&A Wrap up (5 min)

## Resources
- Read this assignment from CS department of Utah [Estimation and Confidence Intervals](https://www.cs.utah.edu/~jeffp/teaching/cs3130/homeworks/hw7.pdf)
