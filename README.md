# Conducting RFM Analysis on a retail sales data set

## RFM stands for recency, frequency and monetary analysis. RFM analysis is usually done on transactions data. The data we used contains details about online transactions from year 2009-2011.

### Task 1
- The first thing you need to do is to create an RFM view for each customer. What is RFM view?

- You will need to compute the following for each customer:

- The number of times a customer has made transactions. If in a single day a customer has made 3 transactions, count them as 3 separate transactions. This is the frequency in RFM

- The total and average revenue per customer. To arrive at revenue, you will need to multiply the Quantity and Price columns. You will also need to clean the Price column for any data quality issues. This will become the monetary term in RFM

- Lastly you will need to find the recency of the last purchase. This can be computed by finding the number of days that have elapsed from the last purchase each customer has made. You can use a base date of 01/01/2012 to compute recency. Find out the number of days elapsed from 01/01/2012 for each customer's most recent purchase.


### Task 2
- Once you have the RFM table, you will need to analyze this table further.

- One of the things you can analyze is to find the vintage of customers. You can find out for which ranges of recency, is the company realizing around 75% of the total revenue.

### Task 3
- Once you have identified the customers by their recency and how much revenue these customers bring, the next task is to find out within the subset of data identified above, for what ranges of frequency is ~65% of the revenue in the subset realized.
