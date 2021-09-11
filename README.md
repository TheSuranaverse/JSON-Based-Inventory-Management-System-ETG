# JSON Based Inventory Management System

The phrase **"Inventory Management"** may strike terror through your very being. Perhaps it brings back nightmares from your high-school cashier job “back in the day”, when you had to spend hours counting endless rows of cereal boxes or racks of women’s jeans by hand. But now, as a small business owner, you have likely realized inventory control is absolutely necessary if you intend to run an efficient business and make money in the process.

## Problem:
In today’s competitive marketplace, one can’t afford to lose money anywhere within their business operations. Keeping track of what items are in stock and how much of them there are, and where they are located can become a big challenge if not handled properly. Storage costs also quickly accumulate for many businesses. So it’s very important to keep track of exactly how many of each item you have in stock, along with how much you have on order.

## Objective:
The main purpose of inventory management is to help businesses easily and efficiently manage the **ordering, stocking, storing and using of inventory**. By effectively managing the inventory, one can always know what items are in stock, how much of them there are, where they are located, etc.

## Brief Introduction:
The **Inventory Management System** here, efficiently tracks inventory from purchase to the sale of goods, and works on **NoSQL** based database. It manages the goods, keep track of stocks and also track sales done using the power of Python and json. Furthermore, it saves a lot of time and efforts of the shopkeepers and facilitates them in the tedious task of managing inventory and sales.

## Working:
This project is mainly divided into two parts:

#### Keeping Track of Stocks in Inventory: 
- **INTRODUCTION:** A **menu driven program** which performs following function: 1) `UPDATE AN ITEM`  2) `ADD NEW ITEM`  3) `DELETE AN ITEM`. It reads the details of the product stored in an inventory from `record.json` file and as per user command it updates the inventory and `record.json` file.
- **IMPLEMENTATION:** The **"Product ID"** is stored as a **"key"**, while all the details of the product like `Product's Name`, `Product's Company`, `Product's Quantity`, `Product's Type`, `Product's Price` is stored in the form of a dictionary as values of the key **"Product ID"**. Every time user update/delete an existing item or add a new item, dictionary containing the details is updated and `record.json` file is updated at the end.
- **RESULT:** Keeping track of products in inventory becomes super easy and comes in handy whenever the user order for new stocks or wants to get update of his current stock of products.
- **UPGRADE:** As per user requirement more features can be added like 
  - Under `UPDATE AN ITEM` we can create more features which asks whether the manager want to update the item's price only or just quantity or both.
  - More attributes can be stored about product's details like it's `Expiry Date`, and if the user has more than one inventory then it can also store `Location` and many more.

#### Keeping Track of Sales and Updating the Inventory Simultaneously: 
- **INTRODUCTION:** A **menu driven program** which performs following function: 1) `GENERATE BILL OF EACH SALE`  2) `UPDATE THE INVENTORY AFTER EACH SALE`. It reads the details of the product stored in an inventory from `record.json` file, updates it after each transaction and also maintain `sales.json` file which keep track of each sales done. 
- **IMPLEMENTATION:** A **menu driven program** which asks for details of the purchased products i.e. `Product ID` and `Quantity`. Once detail of a product is entered, it asks the user again whether they want to enter more products or not. Once this task is done, the program asks for customer's details (`Name`), and if entered, it generates a bill automatically with appropriate `Bill No.` and `Date & Time` of the product purchased. Then it updates our inventory `record.json` file and append the new transaction in `sales.json` file.
- **RESULT:** Keeping track of sales becomes super easy and can easily access previous transactions history. Also stocks are updated automatically after every transaction and thus making inventory management more flexible.
- **UPGRADE:** As per user requirement more features can be added like 
  - More attributes can be added in the "Bill" generated like details of customer, accounting for tax on products, etc.

## Programming Language:
- **Python** 
  - **Libraries Used:** json, datetime, collections
 
## Tools Used:
- **Google Colab:** To write and create `.ipynb` and `.json` files.
- **Git:** To track the changes made to a file, so to have a record of what has been done and also to push our project to Github.

## Author
[Subham Surana](https://github.com/Neklaustares-tPtwP)

## Connect with me
- [My LinkedIn Profile](https://www.linkedin.com/in/subham-surana/)
- [My Kaggle Profile](https://www.kaggle.com/subhamjain)
