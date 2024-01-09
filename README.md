**Customers Who Bought All Products**

The Customer table contains information about customer_id and product_key.
This table may contain duplicates rows. 
customer_id is not NULL.
product_key is a foreign key (reference column) to Product table.
The Product table contains product_key, which is the primary key (column with unique values) for this table.
Write a solution to report the customer ids from the Customer table that bought all the products in the Product table.
Return the result table in any order.
