# Linear Regression Model for Property Price Prediction in Pune, Maharashtra

This project focuses on developing a linear regression model to predict the price of properties in Pune, Maharashtra. The data set used for this project is sourced from Kaggle. Exploratory Data Analysis (EDA) was performed to understand the relationship between property prices and various parameters.

### The following libraries were used for this project:

1) Plotly for interactive visualization
2) Pandas for data manipulation
3) Numpy for numerical calculations
4) Scikit-learn for building the linear regression model
5) Train-test split for splitting the data into training and testing sets

## Data Set
The data set used in this project contains information about different properties in Pune, Maharashtra. The data set includes the following columns:

1) Area
2) Location
3) Price
4) Bedrooms
5) Bathrooms
6) Balcony
7) Type

The 'Price' column is the target variable and the other columns are the predictor variables.

## Exploratory Data Analysis
EDA was performed to gain insights into the relationships between the target variable and the predictor variables. The following visualizations were used for the EDA:

Scatter plot
Histogram
Box plot
The EDA revealed that the price of properties in Pune is most strongly correlated with the 'Area', 'Bedrooms', and 'Bathrooms' and categorical data like Clubhouse, availability of hospitals, parks etc near the locality columns. These columns were used as the predictor variables for the linear regression model.

## Feature Engineering

Feature engineering was performed to improve the performance of the linear regression model. The following feature engineering techniques were used:

### Outlier removal

Outliers were removed from the data set using the interquartile range (IQR) method. One-hot encoding was used to convert categorical variables such as 'Location' and 'Type' into numerical variables that could be used in the linear regression model. Feature scaling was used to normalize the predictor variables so that they had a mean of 0 and a standard deviation of 1.

## Linear Regression Model
A linear regression model was developed using scikit-learn. The data set was split into a training set and a testing set using the train-test split function. The model was trained on the training set and tested on the testing set. 

The linear regression model was able to predict the price of properties in Pune with an effective degree of accuracy. The MSE was low, and the R2 score was high. This indicates that the model is a good fit for the data set and can be used to make predictions about property prices in Pune.

## Conclusion
In conclusion, this project demonstrated the effectiveness of linear regression models in predicting the price of properties in Pune, Maharashtra. The EDA and feature engineering techniques used in this project helped to improve the performance of the model. The linear regression model developed in this project can be used to make  predictions about property prices in Pune.
