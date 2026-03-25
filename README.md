# Target-Brazil-Data-Driven-E-Commerce-Performance-Analysis-using-SQL

Target is a globally renowned brand and a prominent retailer in the United States. Target makes itself a preferred shopping destination by offering outstanding value, inspiration, innovation and an exceptional guest experience that no other retailer can deliver.

This particular business case focuses on the operations of Target in Brazil and provides insightful information about 100,000 orders placed between 2016 and 2018. The dataset offers a comprehensive view of various dimensions, including the order status, price, payment and freight performance, customer location, product attributes, and customer reviews.

By analysing this extensive dataset, it becomes possible to gain valuable insights into Target's operations in Brazil. The information can shed light on various aspects of the business, such as order processing, pricing strategies, payment and shipping efficiency, customer demographics, product characteristics, and customer satisfaction levels

**Dataset schema:**

![image](SQL_imgs/ReadMe_1.png)

**Analysis Performed:**

**1. Conducted Exploratory Data Analysis (EDA) : **

  - by examining the dataset structure, validating data types in the customers table, identifying the order date range, and analysing customer distribution across cities and states.
  
**2. Performed in-depth trend analysis:**

- by evaluating year-wise growth in orders, identifying monthly seasonality patterns, and analysing order distribution across different time intervals as mentioned below

  0-6 hrs: Dawn

  7-12 hrs: Mornings

  13-18 hrs: Afternoon

  19-23 hrs: Night

**3.Analysed the evolution of e-commerce operations in Brazil:**

- by computing month-on-month order volumes across states and assessing customer distribution geographically.
  
**4.Evaluated the economic impact of e-commerce activity**
  
- by calculating the percentage increase in order costs (2017–2018, Jan–Aug), and deriving the total and average order price and freight value at the state level.
  
**5. Conducted logistics and delivery performance analysis**

- by computing delivery time and deviation from estimated delivery, and identifying top/bottom states based on average freight cost, delivery time, and delivery efficiency.
- Calculated the delivery time and the difference between the estimated & actual delivery date using the following formula:

**time_to_deliver** = order_delivered_customer_date - order_purchase_timestamp

**diff_estimated_delivery** = order_estimated_delivery_date - order_delivered_customer_date

**6.Analysed payment behaviour trends:**

- by evaluating monthly order volumes across payment types and assessing order distribution based on payment instalments.
