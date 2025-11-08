# sql50



#1757. Recyclable and Low Fat Products
# Write your MySQL query statement below
SELECT 
    product_id 
from    
    Products
where 
    low_fats ="Y" and recyclable ="Y";
