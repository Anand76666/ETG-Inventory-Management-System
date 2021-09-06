# ETG-Inventory-Management-System
I've made an inventory management system that works on NoSQL based dataset.
I have two JSON files, 'record' and 'sales'.
New Inventories can be added and simultaneously get updated in 'record.json'
Purchasing items can be done by the customer and simultaneously get updated in 'record.json'and 'sales.json'.
When a customer purchases any item, it is checked whether the item matches the product Id or not.
If the quantity of a product that the customer wants to purchase exceeds the originally available quantity, an appropriate message is displayed and the purchase can't be made.
The total Bill amount is generated based on the purchases made.
Each transaction made by the customer is updated accordingly to the 'sales.json' file.
Each transaction display the productId, quantity purchased, and total bill amount.
I've added 5 features per product id.
Product name.
Price.
Quantity.
Date of Manufacture.
Date of Expiry.
My project can do the following things.
Add Items to the Inventory.
Update the Inventory after adding items.
Purchasing items by Customers from the Inventory.
Update Inventory after purchase.
Generate the total Bill.
Display total number of transactions.
