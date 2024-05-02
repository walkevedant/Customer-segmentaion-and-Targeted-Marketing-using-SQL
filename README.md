# Customer segmentaion and Targeted Marketing using SQL

Problem Statement:
- To perform RFM Analysis for a retail store.
- The stores need to adjust their marketing budget and have better targeting of customers so they need to know which customers to focus on and how important they are for the business.
R: Recency (More points for customer who made purchase recently
F: Frequency (More points for customer who purchase many times
M: Monetary (More points for customer whose purchase value is larger

Objective: Developed a customer segmentation strategy to help a retail store optimize marketing and customer engagement based on Recency, Frequency, and Monetary (RFM) analysis.

Steps Taken:

Created a new MySQL database and imported transaction data into a table.
Calculated bill amount for each invoice to understand the monetary value of each transaction.
Aggregated customer details, including recency, frequency, and monetary values.
Performed RFM analysis to calculate recency, frequency, and monetary scores for each customer.
Divided recency, frequency, and monetary values into 5 quantiles for segmentation.
Calculated RFM scores for customers based on quantiles, with recency scoring on a 1-5 scale, frequency and monetary combined into a single score.
Segmented customers into 11 groups (e.g., Champions, Loyal Customers, Recent Customers) based on RFM scores and provided actionable insights for each segment.

Results:

Identified key customer segments for targeted marketing efforts.
Provided strategic recommendations for engaging with each customer segment.
Improved the retail store's ability to focus on high-value customers and reactivate at-risk customers.



