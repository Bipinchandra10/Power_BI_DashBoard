# Power_BI_DashBoard
Overview
I analyzed a dataset of over 60,000 sales transactions worth $4.05 billion. The goal was to build an interactive dashboard to track sales performance across different regions, product categories, and sales channels, while also finding any errors or unusual data in the system.

Data Cleaning and Preparation
Before creating the dashboard, I cleaned and prepared the dataset:

Removed duplicate order records using the order ID.

Standardized text fields (fixed capitalizations and trimmed extra spaces).

Converted Excel date serial numbers into actual readable dates.

Calculated missing values for unit prices, quantities, and discounts.

Labeled blank sales channels as "Unknown" so the data wouldn't be skewed.

Created a rule to flag transactions where the profit margin was higher than 60%.

Main Findings
Overall Numbers: The total sales were 4.05B, bringing in 1.12B in profit (a 27.7% profit margin) across 60,242 orders.

Top Selling Products: Electronics brought in the most sales ($3.51B). Laptops were the single biggest driver, generating 1.75B.

Peak Season: September was the best month for sales across all years, reaching 417M.

Sales Channels: Distributors were the top channel (1.06B in sales), followed by Marketplaces (1.02B) and Retail Stores (1.01B).

Red Flag Analysis
While reviewing the data, I found about 30 customer accounts that showed profit margins over 60%. For example, customer CUST-06929 had 67.7M in sales with $67.2M listed as profit. These accounts were flagged as potential errors (such as missing product cost data or wrong pricing) so the business team can double-check them.
