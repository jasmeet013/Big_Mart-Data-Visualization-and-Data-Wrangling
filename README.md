# Big_Mart-Data-Visualization-and-Data-Analysis
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.

Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

## Tools and Technologies:
Python
scikit-learn / sklearn
Pandas
NumPy
matplotlib
An environment to work in - something like Jupyter Notebook

## Objectives in this project:
Perform data cleaning on the dataset
Make a EDA report
Visualize the distributions of various features and correlations between them
Feature engineering to extract the correct features for the model
Build a regression model to predict the outlet sales

## Dataset description
The dataset has 8524 entries with 13 columns.The description of each columns is given below:

## Missing values in the dataset and mis-coded data:
Item_Fat_Content: Some of ‘Low Fat’ values mis-coded as ‘low fat’ and ‘LF’. Also, some of ‘Regular’ are mentioned as ‘regular’.
Item_weight: this feature is with some missing values.
Outlet_Type:this feature is with some missing values .
## WorkFlow:
The workflow for the project is described in steps given below:
Perform data cleaning using pandas library. Which includes replacing the miscoded information and handling missing data.
Make a Exploratory Data Analysis on the data using pandas.
Visualize distributions and correlation of features using seaborn and pandas using distplot,boxplot,jointplot,plotbar,pairplot,countplot
Build a linear regression model taking the selected features through feature engineering
Pedict the item_outlet_sales for the test data
Save the Big_Mart Data Frame into csv output file

 
