# Restaurant-Designing-using-Yelp-Data
Link to Yelp Dataset: https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset

This was a massive project in terms of processing data, pushing to Azure SQL and querying it using Python. 
First, I had to convert 5 JSON files related to business, checkins, reviews, tips and users into Pandas dataframes. A lot of attributes were multivalues, so we had to split them into separate columns, which widened the shape of the dataset. Then, using the username, and host address details, I pushed these dataframes into the Azure SQL Server database.
I accessed the Azure SQL Server database using a Google colab instance and then created new SQL tables for each of these dataframes by defining the datatypes, primary and foreign keys. Then, using these SQL tables I drafted queries to get insights about customer base, popular cuisines and preferred dishes in order to set up a restaurant.
