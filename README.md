# ETG_InventoryManagementSystem
# Introduction
Inventory Management system is used to manage, add, update and access items from inventory. It includes features for billing and also sales transaction information .
# Tools Used
In this particular project Jupitor Notebook is used and the complete code is written using PYTHON.
# ADDING FILES TO INVENTORY
In this project, the inventory is created and items are stored in in the inventory.
Then it is stored as Inventory.json and from here we access the inventory for addition of items and quantity or adding new attributes.
Then its updated back and stored. Here I have used this file to add more items to inventory and also more attributes to items.
# PURCHASE DETAILS
Here the file is read and accessed. It is then used and the purchase is made.
Each item purchase checks for any offer applicable and offer gets applied to the bill if there are any offers available for a particular project. The total bill amount will have deduction based on offer and it prints a bill.
The bill will contain Name of Store, Name of customer, ProductID, name of product, quantity, price , offer applied (if any), Total bill amount and also Time and Date of purchase.
If user asks for quantity more than available then the system prints a message stating the quantity available.
The change in quantity of item purchased will be updated and written to json file , so that the inventory always shows correct available data after purchase.
# Creating a Sales Transcript
Next we create a sales transaction for each of the sale that takes place with unique transaction id. This happens only if an item is successfully purchased by the customer.
This contains details like customer name, product ID, product Name , amount , offer and quantity.
It  is stored to a json format, as sales.json.
This file is updated each time the sales occurs.

# References
References used are ETG SKILL INDIA FOR PYTHON AI/ML tutorials, W3Schools.
