# Amazon Sales Analysis

# Amazon Sales Analysis 

## Introduction
The "Amazon Sales Analysis" project is a Python-based data analysis effort focused at exploring and comprehending sales data received from Amazon. The project analyses and visualizes the dataset using a variety of Python modules, including NumPy, Pandas, Matplotlib, and Seaborn.

## Data Loading and Inspection
The first step is to load sales data from a CSV file using Pandas. The dataset contains 128,976 entries in 21 fields, including Order ID, Date, Status, Sales Channel, Quantity, Amount, and others. Initial inspection with methods such as 'head()', 'info()', and'shape' gives a brief overview of the data structure.

## Data Cleaning
The dataset is cleaned up to improve its usefulness. Unrelated or blank columns, such 'New' and 'PendingS', are removed. Null values are handled by removing rows or filling in missing data. Data types are modified to ensure consistency, and columns like 'Date' are turned to datetime objects for improved analysis.

## Exploratory Data Analysis (EDA)
### 1. Size Analysis
The distribution of purchases by size is investigated using count plots, demonstrating that M-Size is the most popular among buyers.

### 2. Grouping by Size
Grouping the data by size provides a more in-depth insight of the number of products sold for each size. The data reveals that M-Size products account for the majority of sales.

### 3. Courier Status and Order Status
Analysing shipping methods and order statuses using count plots reveals that couriers ship the bulk of orders.

### 4. Category Distribution
A histogram visualizes the distribution of purchases across different product categories, showcasing T-shirts as the most popular goods.

### 5. B2B Analysis
The project contains a pie chart displaying the distribution of Business-to-Business (B2B) and retailer buyers, which shows that 99.3% of purchasers are retailers.

### 6. Fulfilment Analysis
A pie chart shows the distribution of fulfillment methods, with Amazon serving as the dominant fulfilment service.

### 7. Scatter Plot and State-wise Distribution
Scatter plots are used to investigate the correlations between product categories and sizes. Furthermore, state-specific distribution charts reveal the geographical concentration of buyers, with Maharashtra having the biggest number of clients.

## Conclusion
The Amazon Sales Analysis project gives useful information on client preferences, popular product categories, and geographical distribution. This information can be used by the company to make more informed decisions, optimize inventories, and improve customer happiness.
