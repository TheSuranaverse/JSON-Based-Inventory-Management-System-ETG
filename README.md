# JSON Based Inventory Management System

The phrase **"inventory management"** may strike terror through your very being. Perhaps it brings back nightmares from your high-school cashier job “back in the day”, when you had to spend hours counting endless rows of cereal boxes or racks of women’s jeans by hand. But now, as a small business owner, you have likely realized inventory control is absolutely necessary if you intend to run an efficient business and make money in the process.

## Problem:
In today’s competitive marketplace, you can’t afford to lose money anywhere within your business operations. Keeping track of what items are in stock and how much of them there are, and where they are located can become a big challenge if not handled properly. Storage costs also quickly accumulate for many businesses. So it’s very important to keep track of exactly how many of each item you have in stock, along with how much you have on order.

## Objective:
The main purpose of inventory management is to help businesses easily and efficiently manage the ordering, stocking, storing and using of inventory. By effectively managing your inventory, you'll always know what items are in stock, how much of them there are, and where they are located.

## Brief Introduction:
The Inventory Management System here, efficiently tracks inventory from purchase to the sale of goods. It manages the goods, keep track of stocks and also track sales done using the power of Python and json. Furthermore, it saves a lot of time and efforts of the shopkeepers and facilitates them in the tedious task of managing inventory and sales.

## Working:
This project is mainly divided into two files:

 - **Keeping Track of Stocks in Inventory:** In this part, we create a records.json file which contains all the Inventories with details like product id (barcode), name, quantity, price, isAvailable, Expiry date. Here we can add new goods in the inventory and the records will be stored in records.json file.

- **Keeping Track of Sales and Simultaneously Updating the Inventory:** In this part, a) We enter the transaction or purchase details like product id,no. of items purchased,name of customer, mobile number of customer. b) If the purchased items are available in inventory, then Bill is generated. c) The detailes of the transactions are then stored in sales.json file with attributes like total transactions,transactio id,date,time, product name,total amount of purchase, customer name and customer mobile number.

## Programming Language:
- **Python** 
  - **Libraries Used:** json, collections
 
## Tools Used:
- Google Colab

