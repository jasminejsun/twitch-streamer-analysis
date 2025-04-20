# twitch-streamer-analysis

## About
This mini-project is an analysis on the top 1000 twitch streamers from this [Kaggle dataset](https://www.kaggle.com/datasets/aayushmishra1512/twitchdata/data) for the course SC1015: Into to Data Science and Artificial Intelligence.

## Problem Definition
Can we predict the popularity of a Twitch streamer (measured by watch time) based on their streaming habits, and engagement metrics?

## Data Preparation and Cleaning
- Found a dataset from Kaggle including the top 1000 twitch streamers
- Performed data cleaning such as checking for null values, duplicates, etc.

## Exploratory Data Analysis
- Initial numerical analysis of data
- Used correlation matrices and pair plots to find strong relations between pairs of variables

## Models Used
1. Linear Regression (applying multiple variables to predict a streamer's watch time in minutes)
2. Random Forest Regression (applying multiple variables to then perform many decision trees to predict a streamer's watch time in minutes)

## What we learned
- Applying multiple variables to a linear regression
- Standardizing features (StandardScaler from sklearn)
- Random Forest Regression from sklearn
- Collaborating using GitHub
- How to handle heavily skewed datasets

## Conclusion
- Yes, it is possible to predict the popularity of a Twitch streamer with good accuracy
- It is important to focus on factors like viewer engagement and streaming consistently as a top streamer.
- Watch time and average viewers are critical metrics to take in account

## References
- https://www.geeksforgeeks.org/multiple-linear-regression-with-scikit-learn/
- https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html
- https://www.keboola.com/blog/random-forest-regression
- https://medium.com/@jimmy9728/random-forest-regression-how-it-can-be-applied-in-python-dd8d18ee845b
- https://www.geeksforgeeks.org/random-forest-regression-in-python/

## Contributors
- @jasminejsun (Jasmine Sun - N2402658K)
- @peterli135 (Peter Li - N2402585L)
