## This is a coffee shop database management system, with an Entity-Relationship Diagram (ERD) and relational databases. It's designed to streamline inventory management and boost revenue through targeted advertising.
We are a chain of coffeehouses and roastery services and are trying to digitize our data management processes, especially how our product inventory, customer database, transactions and supplier database is stored and use it to our business advantage. We are interested in knowing how our products perform and improve our relationship with our ingredient supplier as well. We want our database to reflect our core business process and help us maintain the relationship between customers, suppliers and the products that we offer.

## General Information:
### Note - we have used a key attribute to auto generate primary keys unique to each table at insertion.

1.	Each product is described by a unique product ID, name, price, and category.
2.	Each store has a unique store ID, name, store revenue, location and operation cost.
3.	Each supplier has a unique supplier ID, supplier Name.
4.	Each supplier supplies at least one product but there can be multiple products supplied by the same supplier.
5.	Each supplier is identified by a unique key called supplier ID.
6.	Each customer has a unique customer ID, First and Last Name and a contact information (Phone Number).
7.	Each OrderDetail has a unique order Id, Order date, and order unit price.
8.	Each customer will place at least one order.
9.	An order can only be placed by one customer, an order will have at least one product.
10.	One product can belong in multiple orders.
11.	An order can be placed only at one store, but a store will have multiple orders.
12.	Each Customer who will place an order will only have one Phone number to be entered.
13.	The supplier, store and the ingredients supplied by that supplier are linked by the ternary relationship called Supply which stores the information about unit price of the ingredients supplied,quantity supplied, and supplier order date.
14.	The Orderdetail and Customer are linked through the relationship Order.
15.	The Orderdetail and Product are linked through a relationship called Place, which also stores the quantity of the products ordered.
16.	The details about Product and Product Ingredients are linked by the relationship Prepare which also stores the information about the quantity of ingredient required for preparing each product.
17.	The OrderDetail and Store are linked through a relationship Belong.

## Mission statements
### Currently Terpresso business is witnessing a deteriorating condition of its inventory, as a coffeehouse that has pop up stores, we want to have the following information at our fingertips, so as to evaluate Terpresso business requirements better and optimize profits. In the end, we want Terpresso to venture out further and improve their customer relationship services.

1.	What are the Ranked most and least selling products?
2.	What are the top 3 most and least profitable products?
3.	Who are Terpresso’s most frequently returning customers and their contact details?
4.	What is the store information and the total sales profit per store?
