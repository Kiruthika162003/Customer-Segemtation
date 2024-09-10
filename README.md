
## Title
Customer Segmentation for Retail Business

## Problem Statement
As businesses grow, it becomes challenging to understand each customer individually. A data-driven approach is needed to build effective strategies for customer acquisition and retention. Identifying high-value customers and those at risk of churning is crucial for resource allocation and targeted marketing.

## Results Interpretation
Customer segmentation helps businesses develop effective strategies for targeting customers, impacting product development, budget management, and promotional content delivery. It allows companies to understand customer preferences, personalize content, and gain a competitive advantage. Segmentation also aids in pricing strategies, improving customer service, and upselling/cross-selling products.

## Methodology
Customer segmentation involves grouping customers based on shared behaviors or attributes. The process includes:
- Importing necessary libraries
- Reading the dataset
- Visualizing data
- Checking for unique values
- Converting data types
- Formatting columns
- Removing special characters
- Performing Exploratory Data Analysis (EDA)
- Examining null values
- RFM Segmentation (Recency, Frequency, Monetary)
- Standardizing features
- Applying K-Means Clustering Algorithm

## Steps Done
1. Import necessary libraries for analysis
2. Read the CSV data file
3. Set figure size for visualization
4. Remove future warnings in seaborn plots
5. Visualize all columns of the DataFrame
6. View data information
7. Check for unique values in columns
8. Convert data types as needed
9. Format the "size" column
10. Remove special characters from dataset columns
11. Perform Exploratory Data Analysis (EDA)
12. Examine and handle null values
13. Conduct RFM Segmentation
14. Standardize features
15. Apply K-Means Clustering Algorithm

## Dataset
The dataset includes the following attributes:
- InvoiceNo: Unique invoice number
- StockCode: Unique product code
- Description: Product name
- Quantity: Quantity of each product per transaction
- InvoiceDate: Date and time of the transaction
- UnitPrice: Product price per unit
- CustomerID: Unique customer number
- Country: Country where the customer resides

## Conclusion
Customer segmentation is an effective strategy for understanding customer needs and ensuring brand success. Using RFM Modeling and K-Means Clustering, we identified four customer clusters:
- New Customers: Recent transactions, low frequency, low monetary spending
- Lost Customers: Least monetary spending, least transactions
- Best Customers: Frequent spenders, high monetary spending, recent transactions
- At Risk Customers: Last transaction a while ago, less frequent, low monetary purchases

