# Time Series Analysis

### Min-by-Min Plan

- 10 min - What is time series, and how we can sort the data-frame based on date?
- 5 min - Objectives
- 10 min - Review of sorting data-frame
- 10 What is trend? What is seasonality?
- 10 min - Activity: Obtain the trend and seasonality for air passenger dataset
- 25 min - TT: what is time series smoothing and sampling?
- 10 min - Activity: Time Series Sampling and Smoothing on Apple dataset
- 25 min - TT: Using Quandl for Time Series analysis?
- 10 min - Activity: Compute the monthly return for Apple stock data for March 2017
- 5 min - Q&A Wrap Up

## What is histogram? (10 min)

Histogram is one method for estimating density. We explore our own function to the existed ones


## Learning Objectives (Competencies) (5 min)
By the end of this lesson, students will be able to:
1. Describe what is time series
2. Describe how can decompose the time series into trend and seasonality
3. Learn how we can compute the monthly rate of return for a stock data set

## Activity: Obtain the trend and seasonality for air passenger dataset (10 min)

Tasks:

1. Plot the number of passenger based on Month
2. Set the index of data frame by Month
3. Apply the decomposition to data-frame to trend and seasonality of passenger dataset


## Activity: Time Series Sampling and Smoothing on Apple dataset (10 min)

1. Load and plot the "Close" price for Apple Stock Market dataset
2. Sample this dataset and plot it
3. Smooth this time series


## Activity: Compute the monthly return for Apple stock data for March 2017

1. First read this article [Rate of Return](https://www.quantconnect.com/tutorials/introduction-to-financial-python/rate-of-return,-mean-and-variance)
2. Translate the formula to Python code


## Challenges
Check Challenges_Time Series.ipynb

Write a code to compute the followings:

1. How many government accounts have made comments in the month this dataset covers?
2. What day had the most comments? which had the least?
3. We'll define a fradulent account as one that has made more than 40 average clicks per minute. how many fraud accounts are there in this dataset? How many are students in college? Do non-government accounts have a higher probability of being fraud vs the probability of being fraudulent if they are non-government accounts?
4. How many comments mention 'gradiva' and were there more mentions during the day or night?
5. Was the latter half of the month more popular for commenting than the earlier half?
6. What is the average length of a comment coming from people in the irs?

## Q&A Wrap up (5 min)

## Resources
- Watch these series of videos blog [Python Programming for Finance ](https://pythonprogramming.net/getting-stock-prices-python-programming-for-finance/)
