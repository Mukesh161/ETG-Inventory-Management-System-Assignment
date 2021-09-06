# ETG-Inventory-Management-System-Assignment
This project is submission of assignment in Skill India Internship Program of ETG. Assignment is about INVENTORY MANAGEMENT SYSTEM.

#Project includes 4 files:
Adding Product In Inventory.ipynb
Record.json
Buying Product and Generating Sales File.ipynb
Sales.json


#1.Adding Product In Inventory.ipynb
This file helps you to add products to inventory.
Concepts used are File Handling, JSON, Loops, If Else and Data structures.
Initially Record.json is loded with the help of file handling and json module.
While adding the products it asks you for product id, name, weight, price, quantity you want and manufacturer name.
Suppose you have a product which is already listed than entering the id of that product will ask you how much quantity you want to add to the existing quantity and after that quantity gets update in inventory i.e Record.json.
You can keep on adding product as much as you want and finally get out of the adding loop.
To finish adding the products, you need to type 'q' when asked after adding the product.


#2.Record.json
This file is created after adding the products with the help of 'Adding Product In Inventory.ipynb'.
JSON module is used to create this file.
This file works as inventory data i.e what are the products available, what is the price of a product, how much quantity is available and other details.


#Buying Product and Generating Sales File.ipynb
This file helps you buy products from the inventory.
Concepts used are File Handling, JSON, Loops, If Else and Data structures.
Details of product available in inventory are obtained from 'Record.json' file and this file is loaded into the program with the help of JSON module.
After getting details from inventory, it is shown to you (YOU as BUYER).
Looking at the list, just eneter the Product ID and than you will be showed quantity that is available and based on availablity you can enter the quantity you want to buy.
Keep on buying the products by giving the commands shown to you, and simultaneously your cart details are shown.
As buying products is finished finally a bill is generated showing the amount of each product as well as the final amount that buyer needs to pay.
While this has finished, Sales file is created with the help of JSON module, which has the buying activity record as per transaction id.
At the end, changes to the 'Record.json' file are made as per the quantity that would be left after the final bill is generated.


#Sales.json
This file has the record of buying products.
Every time a product has been bought, the details are stored with a unique transaction id.
