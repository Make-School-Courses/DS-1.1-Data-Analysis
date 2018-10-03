# Statistical Analysis

### Min-by-Min Plan

- 10 min - What is histogram, and how we can write our own function to calculate histogram?
- 5 min - Objectives
- 10 min - Review histogram
- 10 What is Gaussian Mixture Model (GMM)? What are the GMM parameters?
- 10 min - Activity: Fit a GMM to a given data sample
- 25 min - TT: what is Kernel Density Estimation (KDE)?
- 10 min - Activity: Apply KDE on a given data sample
- 25 min - TT: What is correlation?
- 10 min - Activity: Obtain the correlation among all features of iris dataset
- 5 min - Q&A Wrap Up

## What is histogram? (10 min)

Histogram is one method for estimating density. We explore our own function to the existed ones


## Learning Objectives (Competencies) (5 min)
By the end of this lesson, students will be able to:
1. Describe what is histogram
2. Describe how can fit mixture of Gaussian to fit the data distribution
3. Learn what is correlation and visualize the correlation among features

## Activity: What is Gaussian Mixture Model (GMM)? What are the GMM parameters? (10 min)

Tasks:

1. For a given generated concatenation of two Gaussian random variable, student first visualize its histogram
2. Fit a GMM to their dataset
3. Interpret the GMM parameters to the original data sample


## What is KDE? (5 min)

Kernel density estimation (KDE) is a non-parametric way to estimate the probability density function of a data sample. In other words the aim of KDE is to find probability density function (PDF) for a given dataset.


## Activity: Apply KDE on a given data sample

Task: Write line of codes to fit KDE to the given data sample


## Break (10 min)

## Correlation (10 min)

Correlation is used to test relationships between quantitative variables. Correlations are useful because we can find out what relationship variables have, we can make predictions about future behavior.

## Activity: Obtain the correlation among all features of iris dataset

Task: Plot the correlation by heatmap and corr plot in Seaborn for all features in iris dataset



## Challenges (10 min)

 Write a code to compute the correlation. The formula is [Peasrson Correlation](https://en.wikipedia.org/wiki/Pearson_correlation_coefficient). Compare your code with what we get from df.corr() from Pandas

## Q&A Wrap up (5 min)

## Resources
- Read this blog [KDE ](https://jakevdp.github.io/blog/2013/12/01/kernel-density-estimation/)
