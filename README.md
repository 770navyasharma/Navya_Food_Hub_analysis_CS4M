# Navya_Food_Hub_analysis_CS4M

### Prerequisites
**To run this project, you need to have the following installed:**

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Project Overview
This project involves the analysis of a dataset provided by a food aggregator company, which contains information on various orders made by registered customers on their online portal. The primary objective of this analysis is to gain insights into customer behavior, restaurant performance, demand patterns, and operational efficiency to enhance customer experience and improve business strategies.

### Data Description
The dataset contains the following features:

- order_id: Unique ID of the order
- customer_id: ID of the customer who ordered the food
- restaurant_name: Name of the restaurant
- cuisine_type: Cuisine ordered by the customer
- cost: Cost of the order
- day_of_the_week: Indicates whether the order is placed on a weekday or weekend (Weekdays are Monday to Friday, weekends are Saturday and Sunday)
- rating: Rating given by the customer out of 5
- food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food, calculated as the difference between the restaurant's order confirmation and the delivery person's pick-up confirmation
- delivery_time: Time (in minutes) taken by the delivery person to deliver the food package, calculated as the difference between the delivery person's pick-up confirmation and drop-off information

### Analysis Steps
#### Basic Data Exploration
- Display the top 5 rows of the dataset.
- Display the last 5 rows of the dataset.
- Check the shape of the dataset.
- Check the data types of each feature.
- Provide a statistical summary of the dataset.
- Check for null values.
- Check for duplicate values.
- Identify anomalies or wrong entries.
- Detect and handle outliers.
- Perform necessary data cleaning steps such as dropping duplicates, imputing null values, and treating outliers.

### Order Analysis
- Total number of orders in the dataset.
- Average cost of an order.
- Number of unique customers who have placed orders.
- Restaurant with the highest number of orders.

### Customer Behavior
- Average rating given by customers.
- Variation of ratings between weekdays and weekends.
- Most ordered cuisine type.
- Distribution of orders across different days of the week.
- Restaurant Performance
- Average food preparation time for each restaurant.
- Restaurant with the shortest average food preparation time.
- Comparison of average delivery times across different restaurants.
- Correlation between the cost of the order and the rating given.

### Demand Patterns
- Variation in demand for different cuisine types on weekdays versus weekends.
- Day of the week with the highest average order cost.
- Most common day for orders to be placed.
- Variation of average rating by cuisine type.
- Operational Efficiency
- Average delivery time for all orders.
- Restaurant with the longest average delivery time.
- Relationship between food preparation time and delivery time.
- Impact of delivery time on customer ratings.

### Customer Insights
- Repeat order rate (number of customers who have placed more than one order).
- Percentage of orders receiving a rating of 4 or higher.
