# Retail-Price-Optimization-Based-on-Demand-Elasticity

##Introduction to Price Optimization

Pricing a product is a crucial aspect of any business. A lot of thought process is put into it. There are different strategies to estimate prices for different kinds of products. There are products whose sales are pretty sensitive to their costs, and as such, a slight change in their price can lead to a noticeable difference in their sales. At the same time, there are also products whose sales are not much affected by their worth - these tend to be luxury items or necessities (like certain medicines). 

Price elasticity of demand (EPD), or elasticity, is the degree to which the compelling desire for something changes as its price changes. In general, people desire things less as those things become more expensive. However, for some products, the customers’ desire could drop sharply even with a bit of price increase, and for other products, it could stay almost the same even with a hefty price increase. Economists use the term elasticity to denote this sensitivity of sales to price fluctuations. More precisely, price elasticity gives the percentage change in quantity demanded when there is a one percent increase in price, holding everything else constant.

##Retail Price Optimization in Python
In this machine learning pricing optimization case study, we will take the data of a cafe and, based on their past sales, identify the optimal prices for their items based on the price elasticity of the items. First, you will calculate the price elasticity for each item, then figure out the optimal price. While taking a particular cafe data, one can extend this work to price any product. This machine learning retail price optimization project will focus on the former products.

##Dynamic Pricing Dataset
The data is contained in three CSV files.

##Cafe - Sell MetaData.csv This file has details about sales made by the cafe. 
Columns: Sell ID, Sell Category, Item ID, Item Name

##Cafe - Transaction - Store.csv This file contains information about transactions and sale receipts of the cafe.
Columns: Calendar Date, Price, Quantity, Sell ID, Sell Category

##Cafe - DateInfo.csv This has date information corresponding to the transactions performed.
Columns: Date, Year, Holiday, Weekend, School Break, Temperature, Outdoor

##Application of Machine Learning for Pricing Optimization in Python Project
Primarily, this project focuses on optimizing the prices of various items available in a burger cafe. The solution of this pricing optimization in Python project can be easily used by experts of different industries like medical, hospitality, insurance, etc. For example, an analyst can recommend changes to the prices of various services offered by a hotel depending on the previous residents’ feedback.
