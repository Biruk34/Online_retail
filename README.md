Customer Spending Behavior Analysis Project

Description

This project applies K-means clustering to analyze customer spending behavior and segment customers into distinct groups based on their Frequency, Monetary, and Recency data. By clustering customers, businesses can identify patterns and tailor marketing strategies for different customer segments.

Project Overview

The main steps in this project include:

Data Loading: Importing the dataset containing customer transaction data.
Data Preprocessing: Cleaning the data by handling missing values and ensuring consistency in the data.
Feature Engineering: Creating the Recency, Frequency, and Monetary (RFM) metrics to assess customer behavior.
Clustering: Applying K-means clustering to segment customers based on their spending behavior.
Elbow Method: Using the Elbow Method to determine the optimal number of clusters.
Cluster Analysis: Analyzing and summarizing the characteristics of each customer segment.
Visualization: Visualizing the results of the clustering and providing actionable insights.

Dataset
The dataset contains the following columns:

InvoiceNo: Unique invoice number for each transaction.
StockCode: Unique product code for each product.
Description: Product name.
Quantity: Number of items purchased.
InvoiceDate: Date and time of the transaction.
UnitPrice: Price of each product.
CustomerID: Unique identifier for each customer.
Country: The country where the customer resides.
The RFM metrics used in the analysis are:

Frequency: Number of transactions per customer.
Monetary: Total spending per customer.
Recency: Number of days since the customer's last purchase.

Results
After applying K-means clustering and performing the cluster analysis, the following key insights were observed:

Cluster 0: Moderate frequency, low monetary value, and moderate recency. These customers are regular but not high spenders.
Cluster 1: Low frequency, very low monetary value, and high recency. These customers are inactive and haven't purchased in a while.
Cluster 2: High-frequency, high-monetary value, and very recent purchases. These customers are the most valuable.
Cluster 3: Moderate frequency, moderate monetary value, and low recency. These customers are active but not high-spenders.

Insights:
Cluster 0: Could benefit from targeted promotions to increase spending.
Cluster 1: May need re-engagement strategies such as discounts or email campaigns to bring them back.
Cluster 2: Represents the most valuable customers who should be rewarded with loyalty programs.
Cluster 3: Active customers who could be encouraged to spend more with personalized recommendations.

Conclusion

This project highlights the power of customer segmentation using K-means clustering. By understanding customer behavior through metrics such as Frequency, Monetary, and Recency, businesses can develop targeted strategies for retaining and engaging their customers. The insights gained from this analysis can drive marketing decisions and improve customer retention.


To run this project locally:

Clone this repository:
git clone https://github.com/Biruk34/Online_retail.git
