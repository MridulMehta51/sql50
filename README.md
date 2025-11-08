SQL 50 - LeetCode
Solutions for SQL 50 Study Plan on LeetCode

1757 - Recyclable and Low Fat Products

SELECT product_id
FROM Products
WHERE low_fats = 'Y'
AND recyclable = 'Y'
584 - Find Customer Referee

SELECT name 
FROM Customer 
WHERE referee_id != 2 OR referee_id IS null
595 - Big Countries

SELECT name, population, area
FROM WORLD
WHERE area >= 3000000
OR population >= 25000000
1148 - Article Views I

SELECT DISTINCT author_id as id
FROM Views
WHERE viewer_id >= 1
AND author_id = viewer_id
ORDER BY author_id
