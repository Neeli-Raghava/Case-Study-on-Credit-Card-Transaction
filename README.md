# Case-Study-on-Credit-Card-Transaction

SQL porfolio project.
download credit card transactions dataset from below link :
https://www.kaggle.com/datasets/thedevastator/analyzing-credit-card-spending-habits-in-india

import the dataset in sql server with table name : credit_card_transcations
change the column names to lower case before importing data to sql server.Also replace space within column names with underscore.
(alternatively you can use the dataset present in zip file)
while importing make sure to change the data types of columns. by defualt it shows everything as varchar.

write 4-6 queries to explore the dataset and put your findings 

solve below questions

1- write a query to print top 5 cities with highest spends and their percentage contribution of total credit card spends 

2- write a query to print highest spend month and amount spent in that month for each card type

3- write a query to print the transaction details(all columns from the table) for each card type when
it reaches a cumulative of 1000000 total spends(We should have 4 rows in the o/p one for each card type)

4- write a query to find city which had lowest percentage spend for gold card type

5- write a query to print 3 columns:  city, highest_expense_type , lowest_expense_type (example format : Delhi , bills, Fuel)

6- write a query to find percentage contribution of spends by females for each expense type

7- which card and expense type combination saw highest month over month growth in Jan-2014

9- during weekends which city has highest total spend to total no of transcations ratio 

10- which city took least number of days to reach its 500th transaction after the first transaction in that city
