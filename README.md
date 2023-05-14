# Supermarket Sales - EDA and Modelling
![](https://storage.googleapis.com/kaggle-datasets-images/2133850/3548798/18d00397327e8c6de9bc8a5a4dcb140b/dataset-cover.jpg?t=2022-04-29-11-13-05)
## About the dataset

The growth of supermarkets in most populated cities are increasing and market competitions are also high. 
The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data. Predictive data analytics methods are easy to apply with this dataset.

## Exploratory Data Analysis

I have done Exploratory Data Analysis on this dataset which helped me gain the following insights:
- Finding the most profitable branch
- Finding relationship between Rating and Gross income
- Finding correlation between different variables using heatmap
- Total price distribution segregated by customer type
- Distribution of Rating
- Product line generating the most income
- Busiest hour of the day

## Actionable items for the business so that it can perform better
We can say that though the rating for ‘fashion accessories’ and ‘food and beverages’ is high but quantity purchased is low. Hence, supply for these products need to be increased.

## Modelling - Simple Linear Regression

For the modelling part, the following steps were followed:

1. Data Cleaning
2. Data Pre-Processing
3. Looking at the statistics
4. Splitting the dataset into training and testing
5. Fitting the simple linear regression model
6. Predicting training data
7. Predicting testing data
8. Plotting the training and testing predictions
9. Checking the training accuracy 
10. Checking the testing accuracy
  > Training accuracy:  -12.74%
  > Testing Accuracy:  -12.81%
11. Plotting the line

 
### Creating a python function for prediction
def prediction(x):
    temp=[]
    temp.append(lr.predict([[x]]))
    return temp
