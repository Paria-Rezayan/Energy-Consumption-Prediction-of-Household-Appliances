### **Linear Regression for Energy Consumption Prediction** ###

The prediction of energy consumption has always been an important topic in the field of energy management. The aim of this project is to develop a Linear Regression model that can predict the energy use of house appliances. To achieve this, I will explore and preprocess the dataset, perform exploratory data analysis (EDA), scale the data using Standard Scaler, and finally implement a Linear Regression model both from scratch and using Sklearn.

Dataset:
The dataset used in this regression project can be found at https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction. It contains data related to the energy consumption of different household appliances with 19735 rows and 29 columns. The raw data includes temporal information such as date and time, along with various environmental factors such as humidity and temperature.

Objective:
The main objective of this project is to create a Linear Regression model that can accurately predict the energy consumption of household appliances based on certain features. The Linear Regression model will help us identify which specific features affect energy consumption the most and how they relate to each other.

Methodology:
Exploring the dataset and looking for any missing or non-numerical data points
Preprocessing the data by removing the date column, checking for and removing outlier data using two distinct techniques: Z Score and Interquartile Range (IQR)
Perform EDA using histograms, distplots, and box plots to visualize the distribution of each feature in the dataset
Scaling the preprocessed data using the Standard Scaler technique to ensure that all features were within a similar range
Implemented a Linear Regression model both from scratch and using Sklearn to predict the energy use of house appliances based on the defined features
Evaluating the model's performance using Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, and R2 score
