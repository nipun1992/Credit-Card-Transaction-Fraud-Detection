
# Credit Card Transaction Fraud Detection

### Overview

The problem statement is regarding Fraud detection on credit card transactions.

A sequential Deep Learning ANN model has been created to perform the binary classification between genuine and fraudulent transactions

This project was assigned by BITS Pilani during the third semester of M.Tech Data Science & Engineering.

## Group Members

This project was done by a group of 3 members including:

 - Nipun Gupta
 - Aiswarya S Parvathi
 - Vengadesh S
 
### About the dataset

Link: https://www.kaggle.com/datasets/dermisfit/fraud-transactions-dataset

This dataset is fictional and is trying to simulate real life details. Any similarity to real life cases is purely coincidental. It has the following columns.

trans_date_trans_time: The date and time of the transaction.

cc_num: credit card number.

merchant: Merchant who was getting paid.

category: In what area does that merchant deal.

amt: Amount of money in American Dollars.

first: first name of the card holder.

last: last name of the card holder.

gender: Gender of the cardholder.Just male and female

street:Street of card holder residence

city:city of card holder residence

state:state of card holder residence

zip:ZIP code of card holder residence

lat:latitude of card holder

long:longitude of card holder

city_pop:Population of the city

job:trade of the card holder

dob:Date of birth of the card holder

trans_num: Transaction ID

unix_time: Unix time which is the time calculated since 1970 to today.

merch_lat: latitude of the merchant

merch_long:longitude of the merchant

is_fraud: Whether the transaction is fraud(1) or not(0)

## Libraries Used

The libraries that we used to build this project are:

 - numpy
  ![numpy](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Numpy.png?raw=true)
 - pandas
 ![pandas](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Pandas.png?raw=true)
 - matplotlib
 ![matplotlib](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Matplotlib.png?raw=true)
 - seaborn
 ![seaborn](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Seaborn.png?raw=true)
 - sklearn
 ![skleanr](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Sklearn.png?raw=true)
 - os
 ![os](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/os.png?raw=true)
 - warnings
 ![warnings](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Warnings.png?raw=true)
 - SMOTETomek
 ![seaborn](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Smotetomek.png?raw=true)
 - Counter
 ![seaborn](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Counter.png?raw=true)
 - Sequential
 ![seaborn](https://github.com/nipun1992/Credit-card-transaction-fraud-detection/blob/master/Screenshots/Sequential.png?raw=true)
 
## Steps performed

- Downloaded the dataset
- Read the dataset as a dataframe
- Exploratory Data Analysis
- Data Preprocessing and data cleaning
- Feature Engineering
- Feature importance
- Feature selection
- Feature scaling
- Train test split
- Model Building
- Model compiling
- Model training and testing
- Training vs Validation accuracy and loss comparison
- Model evaluation
- Hyperparameter tuning
