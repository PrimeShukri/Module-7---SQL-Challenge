# Module-7---SQL-Challenge
Module 7 - SQL HW
In this homework assignment, I am asked to apply my new SQL skills to analyze historical credit card transactions and consumption patterns in order to identify possible fraudulent transactions.

The first task is to define a database model to store the credit card transactions data. I decide to use a star schema, with a fact table called transactions and dimension tables called cardholders, merchants, and products.

The transactions table will store the details of each transaction, such as the amount, date, and time. The cardholders table will store information about the cardholders, such as their name, address, and phone number. The merchants table will store information about the merchants, such as their name and address. The products table will store information about the products that were purchased, such as the product name and price.

Once I have defined the database model, I create a new PostgreSQL database using my model. I then import the CSV files provided into the database.

The next task is to analyze the data to identify possible fraudulent transactions. I use a variety of SQL queries to analyze the data, such as:

Finding transactions that were made in a short period of time for a large amount of money.

Finding transactions that were made to merchants in different countries.
Finding transactions that were made for products that the cardholder has never purchased before.

I also use statistical analysis techniques, such as clustering and anomaly detection, to identify possible fraudulent transactions.

Finally, I developed a report of my observations. I include the queries that I used, the results of the queries, and my analysis of the results.

I am confident I have sufficiently used SQL to analyze data and identify possible fraudulent transactions. 
