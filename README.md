# Year on Year E-Commerce Sales Analysis <br>

## Objective: Why are the sales declining? <br>

## Source: Data set is imported from Kaggle. <br>
It was a messy data: <br>
•	It had duplicate rows <br>
•	Inconsistent Countries, Payment modes <br>
•	Dates were in different format etc. <br>

## Data Processing: 
•	With the use of Python, I eliminated the duplicate, provided consistent name to countries, Payment mode & provided consistent format to the dates. <br>
•	Under Ratings, I update it to 0 where the shipping status were pending and shipped. Because under this status the products can't be rated as it doesn't reach to the customers. Provided an average rating by replacing the null values. <br>
•	Under Shipping City, I deleted the rows where the values were null, because the customers were repeated and they were from different country. <br>
•	Under Discount, the values were not in percentage terms. I formatted then as percentage. <br>

## Data Visualization: <br>
•	With that data set and the help of Power BI, I prepared the charts showing Revenue, Quantity & Product category by country. Which explains the larger picture, also added products under drill down function to show the narrow picture of the business. <br>
•	To focus on sales by product and which country or city, created graphs and which compare orders received, revenue & quantities sold. <br>
•	With the discounts, I compared different category & their products. Aim was to understand which categories or products are sold over discounts and especially at what level of discount. <br>
•	With the Order status, I compared different category & their products. Aim was to see overall ratio of cancelled and returned products or product category. I filtered Shipping & Pending as they are under process because their status will change to Delivered, Returned or Cancelled. <br>
•	With Ratings, I compared different categories and products. Aim was to look the effect of product rating on orders. Outcome was highly rated products were ordered more. <br>

## Outcome (according to the data set): <br>
•	Sales are dropped because of massive drop in orders. <br>

