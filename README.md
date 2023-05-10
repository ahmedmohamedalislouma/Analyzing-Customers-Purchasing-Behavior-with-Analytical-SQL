# Analyzing Customers' Purchasing Transactions Behavior Using Analytical SQL

This project focuses on analyzing customer purchasing transactions to gain valuable insights into customer behavior and optimize sales, revenue, customer retention, and churn. By leveraging analytical SQL techniques, we aim to extract meaningful information from the data and make data-driven business decisions. This README provides an overview of the project, its objectives, datasets, steps, and the solutions to specific questions.

## Problem Statement

Understanding customer behavior is essential for businesses to thrive in a competitive market. By analyzing customer purchasing transactions, we can uncover patterns, trends, and segments that allow us to target customers more efficiently. The main objectives of this project are:

- Analyzing customer purchasing transactions data to gain insights into customer behavior.
- Optimizing sales and revenue through targeted marketing strategies.
- Improving customer retention and reducing churn rates.

## Datasets

This project utilizes the following datasets:

1. OnlineRetail: This dataset contains 406,830 rows of retail transactions data. Each row represents a purchase made by a customer and includes information such as the invoice number, stock code, quantity, invoice date, price, customer ID, and country. This dataset provides valuable information for analyzing customer behavior and identifying purchasing patterns.

2. DailyCustomers: The DailyCustomers dataset consists of 574,396 rows of daily purchasing transactions data for customers. Each row represents a purchase made by a customer and includes information such as the customer ID, purchasing date, and the amount. This dataset will be used to answer specific questions related to customer behavior analysis.

## Project Steps

1. Data Exploration: We will start by exploring the OnlineRetail dataset using analytical SQL queries. This step involves gaining a comprehensive understanding of the data, identifying relevant variables, and assessing data quality.

2. RFM Segmentation: Implementing the RFM (Recency, Frequency, Monetary) model to segment customers based on their purchasing behavior. This segmentation technique allows us to categorize customers into different groups and tailor marketing strategies accordingly.

3. Consecutive Purchase Analysis: Answering the question, "What is the maximum number of consecutive days a customer made purchases?" This analysis will involve utilizing SQL queries to calculate the maximum number of consecutive days a customer made purchases from the DailyCustomers dataset.

4. Spending Threshold Analysis: Addressing the question, "On average, how many days/transactions does it take a customer to reach a spending threshold of 250 L.E?" By applying SQL queries to the DailyCustomers dataset, we will calculate the average number of days or transactions it takes for a customer to reach the specified spending threshold.



## Tools and Technologies
The project leverages the following tools and technologies:
- SQL: Used to perform analytical queries and extract insights from the dataset.
- Analytical SQL Functions: Utilized to calculate metrics, perform aggregations, and analyze customer behavior.
- CTEs (Common Table Expressions): Employed to simplify complex queries and improve query readability.
- Window Functions: Used to perform advanced analytical calculations, such as ranking and running totals.
- Toad: An optional tool for executing SQL queries and interacting with the database.

By applying analytical SQL techniques to customer purchasing transactions, businesses can gain valuable insights into customer behavior, make informed decisions, and implement targeted strategies to optimize sales, revenue, and customer satisfaction.

