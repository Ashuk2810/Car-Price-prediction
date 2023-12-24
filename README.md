# Car-Price-prediction
Geely Auto's entry into the US market is backed by a robust model using the "carprice_assignment" dataset. With meticulous data cleaning, visual analysis, and Linear Regression, the model identifies key pricing factors. Geely gains strategic insights, ensuring a competitive edge in decision-making for market success.



![download](https://github.com/Ashuk2810/Car-Price-prediction/assets/97400304/e2d9fa75-80fd-42ad-894d-215770f03bfa)           ![download](https://github.com/Ashuk2810/Car-Price-prediction/assets/97400304/4cf1c942-5bae-42ed-a071-ec6890a5c6a6)


# Introduction to the Problem Statement.

● A Chinese automobile company Geely Auto aspires to enter the US market 
  by setting up their manufacturing unit there and producing cars locally to give 
  competition to their US and European counterparts. They have contracted an 
  automobile consulting company to understand the factor on which the price 
  of cars depends. Specifically, they want to understand the factors affecting 
  the pricing of cars in the American market, since those may be very different 
  from the Chinese market. The company wants to know:
  
● Which variables are significant in predicting the price of a car. 

● How well those variables describe the price of a car.

# Data Description.

● Based on various market surveys, the consulting firm has gathered a large dataset of different types
of cars across the American market.

● Dataset is named as “carprice_assignment” and consists of 205 records and 26 features in it.

● we are required to model the prices of cars with the available independent variables. It will be used
by management to understand how exactly the prices vary with the independent variables. They can
accordingly manipulate the design of the cars, the business strategy etc. to meet certain price
levels. Further, the model will be good for management to understand the pricing dynamics of the
new market

# Data Cleaning Steps

1.Understand Business Problem:

* Gain a clear understanding of the business problem and objectives.
* Import Libraries and Dataset:

2.Import necessary Python libraries.
* Load the dataset, ensuring availability for analysis.

3.Check for Missing Values:
* Identify and handle missing values in the dataset.
 
4.Check for Duplicate Data:
* Scrutinize the dataset for duplicate entries.

5.Clean CarName Column:
* Address issues in the CarName column, ensuring data consistency.

6.Exploratory Data Analysis (EDA):
* Visualize the target variable 'price' using distplot and boxplot.
* Assess the linear relationship between the dependent variable and numerical independent variables.

7.Univariate, Bivariate, Multivariate Analysis:
* Conduct thorough analyses to identify factors affecting the target variable.

8.Feature Engineering:
* Split the CarCompany column into different price ranges (low, medium, high).

9.Data Preprocessing:
* Create a new dataframe with useful features.
* Generate dummy variables for categorical features.
* Scale numerical data for uniformity.
 
10.Select Target and Independent Features:

* Identify the target feature (y) and independent features (x).

11.Data Splitting:
* Split the data into training and testing sets in an 80:20 ratio.

These steps collectively form a systematic approach to data cleaning and analysis, ensuring a reliable foundation for subsequent modeling and decision-making.

In conclusion, our comprehensive analysis reveals that the Random Forest model emerged as the top performer, achieving an impressive accuracy of 95%. This robust model, coupled with meticulous data cleaning and exploration, equips Geely Auto with invaluable insights for a successful entry into the competitive US market.


![Capture](https://github.com/Ashuk2810/Car-Price-prediction/assets/97400304/2f1ba6b0-7223-4384-ae13-eb35b7084ba5)
