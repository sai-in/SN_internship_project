# SN_internship_project
## Problem statement
A company sells products or licenses to industry professionals. We are given a dataset of customers having information
about the size of purchases, the ratio of products used, assigned products, etc.
On the basis of this data, we have to segment those customers who have the potential to become optimized by applying various data analysis techniques and machine learning models. We also have to forecast the maximum product usage these customers can achieve in the future.

## Data description
The dataset contains seven types of attributes which are described as follows-
1. CustomerID - It is a unique ID assign to a customer when a customer purchases
licenses
2. Purchase_date - It represents the date of purchase of the product.
3. Product Size(P_Size) - It is the total number of products purchased by a customer.
4. Product Usage Ratios(P_Ratio) - It represents the ratio of the product being used. If
Product Size and Product Usage ratio are multiplied then give the total number of
products being used.
5. Product Assigned(P_E) - It represents the total number of products assigned by
customers to their employees. Customers will only pay for those products which are
assigned to employees.
6. Segment - The customers are categorized based on which segment they belong to.
There are a total of 5 segments.
7. CustSize - It represents the size of employees in the industry of customers.

Data contains information about 9 products in which there are 9 columns of product sizes, 9 columns of product assigned, and 6 columns of product ratios. As there are only 6 columns of product ratios so we will only consider the respective 6 columns of product sizes and product assigned.

## Following things have been implemented 

1. Data sanity and cleaning
2. Finding the potential customers
3. Training the ML classifiers
4. Forecasting of product usage

