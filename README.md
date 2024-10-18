# ONLINE SALES DATA REPORT
- **Subject:HSB3119-Introduction to Data Science**
- **Class:MAS2**
- **Lecturer:Dr. Emmanuel Lance Christopher VI M. Plan**

## Team Member Evaluation Of Teamwork
#### Team leader:Lê Duy Anh
![image](https://github.com/user-attachments/assets/812c2abc-d115-4d1d-a7e2-f228d2f04462)


## Introduction

This dataset, sourced from [Samruddhi Bhosale on Kaggle](https://www.kaggle.com), contains two key tables that have been merged into one comprehensive dataset for analysis:
- **Orders.csv** :
Order ID (primary key), Order Date, CustomerName, State, City ->Customer details.
- **Details.csv**:
Order ID (primary key) and the details of all the subsequent orders within the Orders.csv ->Order details.

This data can be instrumental for analyzing sales performance, understanding customer preferences, and making informed business decisions.

## Data Discussion

First 10 rows of the table:

![image](https://github.com/user-attachments/assets/83f3622a-4176-4274-bb53-581221cb72df)



The dataset consists of the following columns:

- **Order ID**: Unique identifier for each order.
- **Order Date**: The date when the order was placed.
- **Customer Name**: The name of the customer who placed the order.
- **State**: The state in India where the order was made.
- **City**: The city of the customer.
- **Amount**: Total amount for the order.
- **Profit**: Profit made from the order.
- **Quantity**: Number of items in the order.
- **Category**: The broad category of products (e.g., Electronics, Furniture).
- **Sub-Category**: More specific classification within the category (e.g., Phones, Chairs).
- **Payment Mode**: The method used for payment (e.g., Credit Card, COD).

### Important Columns for Analysis

- **Amount** and **Profit**: Critical for understanding financial performance.
- **Quantity**: Helps gauge product demand.
- **Category**: Essential for market segmentation analysis.
- **Order Date**: For trend analysis over time.
- **Customer Name**:For customer loyalty programs.
- **Payment Mode**:For analyzing payment method frequency usage.

### Data Cleaning/Processing

Before analysis, the dataset needs to be cleaned:
- Converted the `Order Date` column to a proper datetime format for time-series analysis.
- No missing or null values were found in the dataset, so no imputation was necessary.
- Grouped the data to perform aggregated analysis on sales and profit trends.


## Chart Explanations

### 1. Sales Trend Over Time  
#### Key Observations:
- The chart shows that the highest sales amount occurred in **January 2018** and **March 2018**, where the sales reached approximately **60,000**. After March, the sales dropped and gradually decreased throughout mid-year, only to rise again in October and November.
- There is an **initial spike** in sales from January to March, followed by a **significant decline** through the summer months (April to July). Starting from August, the sales begin to rise again, reaching a peak in November, but then showing a slight decline.
  
#### Managerial Decisions:
- **Seasonal Sales Patterns:** This chart reveals clear seasonality in the sales data. The manager can see that sales perform much better in the **early and late months** of the year (likely due to holidays or seasonal demand). Identifying these peaks helps the business:
- **Inventory Management:** The manager can plan to stock up more products in preparation for the peaks in demand during January, March, and the later months like October and November.
- **Marketing Strategy:** Marketing campaigns can be timed to coincide with the pre-peak months to take advantage of customer demand spikes.
- **Resource Allocation:** During the slower months (like May through July), the company can reduce operational costs, possibly reducing marketing spend or production to avoid overstocking.

![tải xuống (14)](https://github.com/user-attachments/assets/fcf0114c-89c1-4385-b743-ecc827d4745a)

---

### 2. Profit vs. Sales by Product Category Chart
#### Key Observations:
- **Clothing:** Despite having the second-highest sales, Clothing generates the highest profit. This suggests that Clothing products have higher profit margins or are more efficiently managed.
- **Electronics:** Although it has the highest sales, Electronics' profit is relatively lower. 
- **Furniture:** Furniture has the lowest sales and profit.

#### Managerial Decisions:
- **Product Prioritization:** The manager can prioritize products within each category based on their profitability. For example, they might focus on promoting higher-profit clothing items or investigate ways to improve the profitability of electronics.
- **Resource Allocation:** Understanding the profit margins of each category can help guide resource allocation decisions. The manager can allocate more resources to categories with higher profit potential and potentially reallocate resources from less profitable categories.
- **Pricing Strategy:** The chart can inform pricing decisions. If a category has high sales but low profit, the manager might consider increasing prices to improve profitability. Conversely, if a category has low sales but high profit, they might consider lowering prices to stimulate demand.
  
![tải xuống (36)](https://github.com/user-attachments/assets/e59833ee-a34a-4a84-b70c-2f9fac4e0721)

---
#### 3.Top Customers by Revenue

#### Key Observations:
- Harivansh is the top customer by a significant margin, with a revenue far exceeding the others.
- Madhav and Madan Mohan follow closely behind, forming a clear tier of high-revenue customers.
  
#### Managerial Decisions
- **Customer Segmentation:** The chart suggests a potential for segmenting customers into high-value, mid-value, and low-value groups. This segmentation can inform targeted marketing strategies and customer relationship management efforts.
- **Customer Loyalty:** The top customers, particularly Harivansh, Madhav, and Madan Mohan, may represent a core customer base that is highly loyal and valuable to the business. It's essential to retain and nurture these customers,possibly through loyalty programs or personalized marketing.
- **Sales Performance Analysis:** The chart can be used to identify underperforming customers and investigate the reasons behind their lower revenue. This analysis can lead to improvements in sales processes, product offerings, or customer service.
  
![tải xuống (40)](https://github.com/user-attachments/assets/30330c44-bec2-4184-97a7-1c49ff184e3e)

---
#### 4.Frequency of Payment Mode Usage

#### Key Observations:
- **Cash on Delivery (COD)** is the most frequently used payment method, significantly outpacing other options. This suggests that customers may prefer the security of paying upon delivery.
- **UPI (Unified Payments Interface)** comes next, indicating a growing trend in digital payment methods among consumers.
- **Debit Card** and **Credit Card** usage is moderate, while **EMI (Equated Monthly Installment)** options are the least utilized. This could reflect customer preferences for immediate payment methods rather than credit-based options.
  
#### Managerial Decisions
- **Customer Preferences:** High usage of COD suggests a need for retaining this option. It may also indicate trust issues with online payments.
- **Promote less-used options:** Consider offering incentives or promotions to encourage the use of Debit Card, Credit Card, and EMI.
- **Negotiate with payment providers:** Negotiate better terms with payment providers based on usage data.
- **Marketing Focus:** Promotions or incentives could be tailored for less popular payment methods to encourage their usage, such as offering discounts for credit card payments.
  
![tải xuống (39)](https://github.com/user-attachments/assets/34a5b6f2-10f3-42ea-be82-75f7734ed6cb)

---

## Conclusion

This analysis of online sales data reveals key insights:

* **Seasonality:** Sales peak in January, March, October, and November.
* **Profitability:** Clothing has high profit margins, Electronics have high sales but lower profit.
* **Customer Analysis:** Harivansh,Madhav and Madan Mohan is the top customers.
* **Payment Method Analysis:** COD is the most frequently used payment method,UPI comes next,showing a growing trend in digital payment methods.

These findings offer valuable guidance for future business decisions. By leveraging the insights from this data analysis, the company can improve inventory management, optimize marketing strategies, prioritize profitable products, and strengthen customer relationships, ultimately leading to increased sales and profitability.

