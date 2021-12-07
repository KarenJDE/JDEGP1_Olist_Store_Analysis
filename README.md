# Olist_Store_Business Analysis

## Abstract 
Olist Store is the largest department store in Brazilian marketplaces which connects small businesses from all over Brazil to channels without hassle and with a single contract. Olist acts as a service provider who helps merchants to manage the sales process including online shopping,and reports of customer satisfaction. Merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners.There is public dataset of orders made in 2016 to 2018 at Olist Store. 

 See more on website: www.olist.com

## Business Analysis Objectives
The objectives of this business analysis are: 
* Sales Performance
  * How many customers, orders, and orders per customer does the company have?
  * What is the number of customers by state?
  * What is the number of orders by month?
  * What are the top 5 product categories?
* Sales Prediction: Predict future sales with purchase date information.
* Are there correlationship between sellers and customers geolocation distribution?
* Reviews Score Analysis: Evaluate the average scores by product category.
* Delivery Performance: Work through delivery performance and find ways to optimize delivery times.

## Problem Statement
We have decided to use SQLite3 to implement the local database as it is very suitable for a small-scale project and easy to use. However, a member failed to making connection at the first time through ODBC Data Source. After doing research, we all successfully connected to Power BI by using connection string directly.
The data source files are provided in csv format and have loaded into a SQLite database with .import method by using SQLite command line tool which is very convenient and efficient to make our database right off the bat.

## Requisition
* Create SQLite Database Connection
  * Install ODBC Driver from http://www.ch-werner.de/sqliteodbc/
  * Connection String: `Driver={SQLite3 ODBC Driver};Database=YourDatabase`
