# Motade-Europe_Bike_Sales
![Europe bike sales dahboard](https://github.com/Motade/Motade-Europe_Bike_Sales/assets/114887240/536219fb-6b22-4618-bc8d-3f642eace149)

## PROJECT OBJECTIVE
This project showcases a high level of expertise in examining extensive sales data to uncover important patterns, identify top-selling products, and derive essential revenue metrics. The objective is to enable data-driven decision-making that can guide strategic improvements to enhance sales strategies.

## ABOUT DATASET
**Nature of Data **: This dataset contains sales-related information, including dates, customer demographics, product details, order quantities, unit costs, prices, and financial metrics.
Attributes:
- Date: The date of each sales transaction.
- Day: The day of the week corresponding to each transaction date.
- Month: The month in which each transaction occurred.
- Year: The year of each sales transaction.
- Customer_Age: The age of the customer making the purchase.
- Age_Group: Categorized age groups of customers.
- Customer_Gender: The gender of the customer (e.g., male, female).
- Country: The country where the transaction took place.
- State: The state or region within the country.
- Product_Category: The broad category to which the product belongs.
- Sub_Category: A subcategory within the product category.
- Product: The specific product being sold.
- Order_Quantity: The number of units of the product ordered.
- Unit_Cost: The cost of each unit of the product.
- Unit_Price: The price at which each unit of the product is sold.
- Profit: The profit generated from the sale.
- Cost: The total cost of the products in the order.
- Revenue: The total revenue generated from the sale.

The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/prepinstaprime/europe-bike-store-sales)

## DATA CLEANING PROCESS
1. **Re-calculated Columns:**: I re-calculated the "Profit," "Cost," and "Revenue" columns due to calculation errors in the original data source.
**Revenue** = Unit_Price * Order_Quantity
**Cost** = Unit_Cost * Order_Quantity
**Profit** = Revenue - Cost

2. **Duplicate Check:** I conducted a check for duplicate records and dropped the duplicates records.


## RESULTS AND FINDINGS
1. Total revenue and profit breakdown by product category: When analyzing the revenue and profit figures categorized by product, it becomes evident that the bikes category takes the lead, bringing in an impressive $69,208,196 in revenue, accounting for a significant 66.34% of the company's total profit. Following closely, the accessories category generates $16,712,646 in revenue, contributing to 24.82% of the company's profit. Meanwhile, the clothing category records $9,255,476 in revenue, constituting 8.84% of the profit.

![image](https://github.com/Motade/Motade-Europe_Bike_Sales/assets/114887240/3c122f08-6309-4c40-adc4-c542d510c221)




