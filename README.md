
# Customer RFM Analysis

## Project Overview

This project focuses on Customer RFM (Recency, Frequency, and Monetary) Analysis to understand customer purchasing behaviour, identify valuable customer segments, and generate meaningful business insights.

RFM analysis is a data-driven customer segmentation technique that evaluates customers based on three key metrics:

- **Recency (R):** How recently a customer made a purchase.
- **Frequency (F):** How frequently a customer makes purchases.
- **Monetary (M):** How much a customer spends over a given period.

The objective is to use transactional data to understand customer value, identify loyal and high-value customers, and support data-driven marketing and business decisions.

## Business Objectives

- Analyse customer purchasing patterns and behaviours.
- Identify high-value, loyal, and inactive customers.
- Segment customers based on Recency, Frequency, and Monetary scores.
- Understand customer contribution to overall revenue.
- Identify opportunities for customer retention and engagement.
- Support targeted marketing and customer relationship management strategies.

## Dataset Description

The project uses an Excel workbook containing five interconnected datasets.

| Dataset | Records | Description |
|---|---:|---|
| Customers | 2,500 | Customer demographics and information |
| Transactions | 20,000 | Customer purchase and transaction details |
| Products | 150 | Product information, categories, and pricing |
| Stores | 40 | Store details and classifications |
| Regions | 6 | Regional information and geographical zones |

### Key Features

**Customers**
- CustomerID
- CustomerName
- Gender
- Age
- City
- RegionID
- CustomerSince
- CustomerType

**Transactions**
- TransactionID
- TransactionDate
- CustomerID
- ProductID
- Quantity
- UnitPrice
- DiscountPct
- SalesAmount
- PaymentMethod
- StoreID
- SalesChannel
- RegionID

**Products**
- ProductID
- ProductName
- Category
- SubCategory
- UnitCost
- ListPrice

**Stores**
- StoreID
- StoreName
- City
- RegionID
- StoreType

**Regions**
- RegionID
- RegionName
- Zone

## RFM Methodology

The analysis follows three major steps:

### 1. Recency
Measures the number of days since a customer's most recent purchase.

Lower recency indicates more recent customer activity.

### 2. Frequency
Measures the total number of transactions made by each customer during the analysis period.

Higher frequency indicates greater purchasing engagement.

### 3. Monetary
Measures the total amount spent by each customer during the analysis period.

Higher monetary value indicates greater customer revenue contribution.

### RFM Scoring

Customers can be assigned scores based on their Recency, Frequency, and Monetary values.

A scoring scale of 1–5 can be used for each metric, creating an overall RFM segmentation framework.

Based on their combined scores, customers can be grouped into categories such as:

- Champions
- Loyal Customers
- Potential Loyalists
- Recent Customers
- At-Risk Customers
- Customers Needing Attention
- Lost Customers

## Tools and Technologies

The project can be developed using the following tools:

- Microsoft Excel – Data inspection and preliminary analysis.
- SQL – Data extraction, transformation, and aggregation.
- Python – Data cleaning, RFM calculations, and customer segmentation.
- Pandas & NumPy – Data manipulation and analysis.
- Matplotlib & Seaborn – Data visualization.
- Power BI – Interactive dashboards and business reporting.

## Expected Business Insights

The analysis aims to uncover:

- Distribution of customers across RFM segments.
- Revenue contribution from different customer segments.
- Identification of high-value and loyal customers.
- Customers showing declining purchasing activity.
- Purchasing trends across different regions and sales channels.
- Opportunities to improve customer retention and revenue generation.

## Project Structure

```text
Customer-RFM-Analysis/
│
├── Dataset/
│   └── Customer_RFM_Project.xlsx
│
├── Notebooks/
│   └── RFM_Analysis.ipynb
│
├── SQL/
│   └── Customer_Analysis.sql
│
├── Dashboard/
│   └── RFM_Dashboard.pbix
│
└── README.md
```

*Note: The structure above is a suggested organization for the project.*

## Conclusion

Customer RFM Analysis provides a systematic approach to understanding customer value and purchasing behaviour.

By combining transactional, demographic, product, and regional information, this project aims to transform raw business data into actionable insights that can help organizations improve customer retention, optimize marketing strategies, and make informed business decisions.

---

**Project Domain:** Business Analytics | Customer Analytics | Data Analysis

**Project Type:** Data Analytics & Customer Segmentation
