#Vedgrow_DS_04 (task 4)
# Customer Segmentation using Clustering

## Project Overview

This project performs customer segmentation using the Online Retail dataset.

The main objective of this project is to group customers based on their purchasing behavior using clustering techniques.

The project uses:

- RFM Analysis
- K-Means Clustering
- DBSCAN Clustering

to identify different customer groups such as:

- Loyal Customers
- Churn Risk Customers
- Regular Customers
- Big Spenders

These insights can help businesses improve customer retention, personalized marketing, and sales strategies.

---

## Dataset

Online Retail Dataset:

https://www.kaggle.com/datasets/vijayuv/onlineretail

The dataset contains transactional information such as:

- Invoice Number
- Product Details
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. RFM Feature Engineering
5. Log Transformation
6. Feature Scaling
7. K-Means Clustering
8. DBSCAN Clustering
9. PCA Visualization
10. Business Insights

---

## Data Cleaning Steps

The following preprocessing steps were performed:

- Removed missing Customer IDs
- Removed duplicate records
- Removed cancelled orders
- Removed negative quantities
- Removed invalid prices

---

## RFM Analysis

RFM stands for:

- Recency
- Frequency
- Monetary

These features were used to understand customer purchasing behavior.

### Recency
How recently a customer purchased.

### Frequency
How often a customer purchases.

### Monetary
How much money a customer spends.

---

## Clustering Algorithms Used

### K-Means Clustering

K-Means clustering was used to segment customers into multiple groups based on RFM values.

### DBSCAN

DBSCAN was used to identify noise and outlier customers.

---

## PCA Visualization

Principal Component Analysis (PCA) was used to reduce dimensions and visualize customer clusters in 2D space.

---

## Business Insights

The project identified different customer groups such as:

### Loyal Customers
- Frequent purchases
- High spending
- Recent activity

### Churn Risk Customers
- Inactive customers
- Low spending
- Low engagement

### Regular Customers
- Moderate purchase activity
- Average spending behavior

### Big Spenders
- High monetary contribution
- Valuable customers for the business


## Business Strategies

### Loyal Customers
- VIP rewards
- Loyalty programs
- Personalized recommendations

### Churn Risk Customers
- Re-engagement emails
- Discount offers
- Retargeting campaigns

### Regular Customers
- Membership plans
- Cross-selling strategies

### Big Spenders
- Premium support
- Exclusive products
- Personalized marketing


## Conclusion

This project successfully performed customer segmentation using clustering techniques on online retail transaction data.

K-Means clustering grouped customers based on purchasing behavior, while DBSCAN identified outlier customers.

The insights generated from this analysis can help businesses improve customer engagement, retention, and marketing strategies.

