
1757 - Recyclable and Low Fat Products
# Write your MySQL query statement below
SELECT product_id from Products
WHERE low_fats="Y" and recyclable="Y"
ORDER BY 1 ASC;



584 - Find Customer Referee
# Write your MySQL query statement below
SELECT name from Customer
WHERE referee_id !=2 or referee_id is NULL;
