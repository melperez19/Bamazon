# Bamazon - A Node.js & MySQL Application

* Created an Amazon-like storefront with the MySQL skills learned thus far. The app takes in orders from customers and depletes stock from the store's inventory. 

* This database will populate with around 10 different products. (i.e. Inserted "mock" data rows into this database and table).
Then running the Node application called bamazonCustomer.js. will first display all of the items available for sale. Include the ids, names, and prices of products for sale.

-The app then prompts users with two messages.
The first asks them the ID of the product they would like to buy.
The second message asks how many units of the product they would like to buy.

Once the customer has placed the order, your application checks if the store has enough of the product to meet the customer's request.
If not, the app will log a phrase like Insufficient quantity!, and then prevent the order from going through.

However, if the store does have enough of the product, the customer's order will be fulfilled.
This means updating the SQL database to reflect the remaining quantity.
Once the update goes through, the customer will be given the total cost of their purchase.

[Click here to demo the bamazonCustomer.js!](https://youtu.be/p7DNw9cgBio)
 
* In addition, a manager specific interface was created to allow the viewing of all inventory, low inventory, adding more stock, and adding new products. Every edit that is saved is automatically updated to the bamazon database.

[Click here to demo the bamazonManager.js!](https://www.youtube.com/watch?v=aURXbVDltV0&feature=youtu.be)
