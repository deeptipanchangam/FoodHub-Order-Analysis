# FoodHub-Order-Analysis
## Context
The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides 
them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app.

## Objective
Analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience.

## Data Description
The data contains the different data related to a food order. The detailed data dictionary is given below.

## Data Dictionary
1. order_id: Unique ID of the order
2. customer_id: ID of the customer who ordered the food
3. restaurant_name: Name of the restaurant
4. cuisine_type: Cuisine ordered by the customer
5. cost: Cost of the order
6. day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
7. rating: Rating given by the customer out of 5
8. food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
9. delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information
