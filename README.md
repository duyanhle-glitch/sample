# ONLINE SALES DATA REPORT
- **Subject:HSB3119-Introduction to Data Science**
- **Class:MAS2**
- **Lecturer:Dr. Emmanuel Lance Christopher VI M. Plan**

## Team Member Evaluation Of Teamwork
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
- **Category** and **Sub-Category**: Essential for market segmentation analysis.
- **Order Date**: For trend analysis over time.
- **City**: For finding cities with top sales .
- **Payment Mode**:For finding mthod of payment with top performance.

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

### 2.Average Profit Margin by Category


#### Key Observations:
- The chart shows that Clothing has the highest average profit margin, indicating that it is more profitable on a per-unit basis compared to Electronics and Furniture.

#### Managerial Decisions:
- **Prioritize product categories:** Focus on promoting and expanding product categories with higher profit margins, such as Clothing.
- **Review underperforming categories:** Investigate the reasons for lower profit margins in Electronics and Furniture and consider strategies to improve profitability.
- **Identify opportunities:** Look for potential opportunities to increase profit margins in all categories, such as optimizing pricing or cost structures.

![tải xuống (27)](https://github.com/user-attachments/assets/a343f04d-d6b7-432a-b529-d8f3034cdad5)


---

### 3.Top 10 Sub-Categories by Sales

#### Key Observations:
- **Highest Sales**: Printers have the highest total sales, followed by Sarees and Bookcases.

#### Managerial Decisions:
- **Prioritize product categories**: Focus on promoting and restocking products with high demand, such as Printers and Sarees.
- **Evaluate underperforming categories**: Investigate the reasons for low sales in products like Stole and Accessories. Consider offering promotions or improving product offerings.
- **Optimize inventory**: Use this data to optimize inventory levels for each product, ensuring adequate stock while minimizing excess inventory.

![tải xuống (33)](https://github.com/user-attachments/assets/89121389-a6d9-4ab4-b54f-0cfb9200774f)

### 4. Sales Distribution by Payment Mode

#### Key Observations:
- The largest portion of sales, **45.6%**, comes from **Cash on Delivery (COD)**, followed by **UPI** at **22.1%**. Other payment methods like debit cards, credit cards, and EMI make up smaller portions, with EMI being the least used at **8.0%**.
- Pattern:** COD is the dominant payment method, indicating that customers prefer paying upon receiving the product. Digital payment options like UPI and debit cards are also widely used, but traditional credit cards and EMI options lag behind.

#### Managerial Decisions
- **Optimize Payment Options:** The high COD usage suggests customers might value security in transactions. The manager could consider enhancing COD services and ensuring smooth returns/refund processes.
- **Promote Digital Payments:** Since UPI has strong usage, offering discounts for digital payments could further increase their adoption, lowering handling costs associated with COD.
- **Expand Payment Options:** Encouraging more customers to use credit cards or EMI through incentives (like installment plans or cashbacks) could help increase higher-value purchases.
Understanding payment preferences helps the business enhance customer experience and optimize transaction costs.

![tải xuống (17)](https://github.com/user-attachments/assets/aa099640-616a-4244-92ae-7eedd330ebfe)


---
#### 5.Top 10 Performing Cities by Sales

#### Key Observations:
- **Indore** has the highest sales amount, indicating it is the top-performing city.

#### Managerial Decisions
- **Resource Allocation:** The manager can allocate more resources, such as marketing efforts or stock, to cities like Indore and Mumbai to maximize revenue.
- **Strategy Development:** Cities with lower sales, like Thiruvananthapuram, might need a revised strategy to boost sales. This could include targeted promotions or understanding local customer preferences.
- **Performance Monitoring:** Regular monitoring can help identify trends over time, such as whether certain cities are improving or declining in performance.
- **Market Expansion:** The manager can consider expanding operations in high-performing cities or investigate potential in lower-performing ones.

![tải xuống (18)](https://github.com/user-attachments/assets/3ef75bb9-c54c-48f8-9323-412bd433279e)

---

## Conclusion
This comprehensive analysis of online sales data has provided valuable insights into customer behavior, product performance, and overall business health. By understanding sales trends, profit margins, and customer preferences, we can make informed decisions to optimize our online sales strategy.By implementing these recommendations, we can effectively leverage our online sales data to drive business growth, enhance customer satisfaction, and maintain a competitive edge in the market.


