# ETG_InventoryManagementSystem
# Introduction
Inventory Management system is used to manage, add, update and access items from inventory. It includes features for billing and also sales transaction information .
# Tools Used
In this particular project Jupitor Notebook is used and the complete code is written using PYTHON.
# ADDING FILES TO INVENTORY
In this project, the inventory is created and items are stored in in the inventory.
Then it is stored as Inventory.json and from here we access the inventory for addition of items and quantity or adding new attributes.
Then its updated back and stored. Here I have used this file to add more items to inventory and also more attributes to items.
# Product Attributes of the Items
Attributes included for each item in this inventory are :
30 items + 1 more added later by accessing file and adding new items.
Each product has:
 ProductID, Name, Producttype, quantity, price, manufacturedby,netweight, form, manufactureDate, Ingredienttype, Flavour.
And  Offer attribute is added later in the code.
# PURCHASE DETAILS
Here the file is read and accessed. It is then used and the purchase is made.
Each item purchase checks for any offer applicable and offer gets applied to the bill if there are any offers available for a particular project. The total bill amount will have deduction based on offer and it prints a bill.
The bill will contain Name of Store, Name of customer, ProductID, name of product, quantity, price , offer applied (if any), Total bill amount and also Time and Date of purchase.
If user asks for quantity more than available then the system prints a message stating the quantity available.
The change in quantity of item purchased will be updated and written to json file , so that the inventory always shows correct available data after purchase.
# Features in Billing
 Takes ProductId and Quantity as input from user.
 It checks for the item entered ,whether entered QUANTITY is available?
 if available purchase takes place , if not it prints saying  "Sorry,the quantity of product available is so and so". If product quantity is zero, then it prints PRODUCT OUT OF STOCK.
 If purchase happens it checks for OFFERS.
 If offer is applicable then it subtracts the OFFER amount from TOTAL amount and prints the AMOUNT to be paid by Customer.
 The bill also contains DATE and TIME OF PURCHASE in it.
 There is an optional code to check if user entered id is ValidItemId or not (incase user is not using bar code scanner and is entering it manually).
# Creating a Sales Transcript
Next we create a sales transaction for each of the sale that takes place with unique transaction id. This happens only if an item is successfully purchased by the customer.
This contains details like customer name, product ID, product Name , amount , offer and quantity.
It  is stored to a json format, as sales.json.
This file is updated each time the sales occurs.
# Sales Attributes in sales transcript
In this the sales file gets updated only if purchase takes place, incase due shortage of quantity or out of stock and the product is not purchased,then this file will not be updated.
Attributes in sales: 
transactionId, ProductName,ProductId, CustomerName,Quantity, Amount(paid), offer on product.

# References
References used are ETG SKILL INDIA FOR PYTHON AI/ML tutorials, W3Schools.
# About Me
I am Leetha Muthamma D M.
I am a student pursuing Engineering under the branch Computer Science and Engineering from Coorg Institue of Technology(CIT).
I am currently in my final year and I have done DBMS mini project on Web Based Internship Management system.
Inventory management system project  is a part of my internship in Skill India Internship on Python for AI/ML by ELite Techno Groups
This project code is written using Python.

