# ANALYSIS OF EUROPEAN BIKE SALES TRENDS AND PERFORMANCE
![Europe bike sales dahboard](https://github.com/Motade/Motade-Europe_Bike_Sales/assets/114887240/1be177f3-fbfd-428b-a219-d74dcbc78443)


## PROJECT OBJECTIVE
This project showcases a high level of expertise in examining extensive sales data to uncover important patterns, identify top-selling products, and derive essential revenue metrics. The objective is to enable data-driven decision-making that can guide strategic improvements to enhance sales strategies.

## ABOUT DATASET
The dataset contains sales-related information, including dates, customer demographics, product details, order quantities, unit costs, prices, and financial metrics.
**Attributes**:
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
![image](https://github.com/Motade/Motade-Europe_Bike_Sales/assets/114887240/ca77fe2a-896a-409b-8e22-809f0e101b3b)

2. Top-performing countries in revenue and profit: The company achieved its highest revenue of $30,814,774 in the United States, closely followed by Australia, which generated $25,427,586. The list of the top 5 highest-performing countries is provided below;
![image](https://github.com/Motade/Motade-Europe_Bike_Sales/assets/114887240/65f99f6e-0ad2-45ac-8736-7eaa2ce33a72)

## RECOMMENDATIONS
Utilizing the provided insights, I suggest implementing the following strategic initiatives to enhance both profitability and market prominence:
1. Addressing the clothing category is of paramount importance since it recorded the lowest revenue and contributed the least profit. A comprehensive assessment of its product range, pricing strategies, and cost-saving measures is imperative.
   
2.The bike and accessories categories, known for their significant revenue contributions, should be examined for potential opportunities through diversification and substantial investments in effective marketing campaigns.

To interact with the dash board click [here](https://motray-my.sharepoint.com/:x:/g/personal/motray_motray_onmicrosoft_com/EeW93fjjzhVGmbY0K4ijwhMBXWjdapzf0OYaaro_5bziCQ?e=fIRCE6&nav=MTVfe0U0RDI2RTdELUY5OTQtNDUyOS04MzRELTJEMEYzNEMzQUE2Q30)

Yours sincerely,

Motunrayo Oguntade.
