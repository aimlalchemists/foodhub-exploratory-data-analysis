# FoodHub: Data Analysis for Restaurant Demand

## Description
In the bustling city of New York, the restaurant scene is thriving. With busy students and professionals relying on dining out, online food delivery services have become a lifeline. One such service, FoodHub, offers a convenient solution by aggregating multiple restaurants into a single smartphone app.

Here's how it works:
- Customers place direct online orders through the app, which are then confirmed by the respective restaurants.
- FoodHub assigns a delivery person to pick up the order.
- Armed with a map, the delivery person heads to the restaurant, waits for the food package, and confirms the pick-up within the app.
- The journey continues as the delivery person transports the order to the customer's location, confirming the drop-off once completed.
- Customers can also rate their orders within the app.
- FoodHub's revenue model involves collecting a fixed margin from the restaurants for each successful delivery.

## Objective
As a Data Scientist at FoodHub, your task is to analyze order data, understand restaurant demand patterns, and enhance the overall customer experience.

## Data Description
The dataset contains various details related to food orders:
- **Order ID:** A unique identifier for each order.
- **Customer ID:** The ID of the customer who placed the order.
- **Restaurant Name:** The name of the restaurant fulfilling the order.
- **Cuisine Type:** The specific cuisine ordered by the customer.
- **Cost of the Order:** The total cost of the order.
- **Day of the Week:** Indicates whether the order was placed on a weekday (Monday to Friday) or the weekend (Saturday and Sunday).
- **Rating:** Customers provide a rating (out of 5) for their order.
- **Food Preparation Time:** The time (in minutes) taken by the restaurant to prepare the food. Calculated based on the timestamps between order confirmation and pick-up confirmation.
- **Delivery Time:** The time (in minutes) taken by the delivery person to transport the food package from the restaurant to the customer. Calculated based on the timestamps between pick-up confirmation and drop-off confirmation.
