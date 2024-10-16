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

### Data Cleaning/Processing

Before analysis, the dataset needs to be cleaned to:
- Handle missing values
- Remove duplicates
- Ensure consistent data types
- Address erroneous entries (e.g., negative profits)


## Chart Explanations

### 1. Sales Trend Over Time  
### Key Observations:
- The chart shows that the highest sales amount occurred in **January 2018** and **March 2018**, where the sales reached approximately **60,000**. After March, the sales dropped and gradually decreased throughout mid-year, only to rise again in October and November.
- There is an **initial spike** in sales from January to March, followed by a **significant decline** through the summer months (April to July). Starting from August, the sales begin to rise again, reaching a peak in November, but then showing a slight decline.
  
#### Managerial Decisions:
- **Seasonal Sales Patterns:** This chart reveals clear seasonality in the sales data. The manager can see that sales perform much better in the **early and late months** of the year (likely due to holidays or seasonal demand). Identifying these peaks helps the business:
- **Inventory Management:** The manager can plan to stock up more products in preparation for the peaks in demand during January, March, and the later months like October and November.
- **Marketing Strategy:** Marketing campaigns can be timed to coincide with the pre-peak months to take advantage of customer demand spikes.
- **Resource Allocation:** During the slower months (like May through July), the company can reduce operational costs, possibly reducing marketing spend or production to avoid overstocking.

![tải xuống (14)](https://github.com/user-attachments/assets/fcf0114c-89c1-4385-b743-ecc827d4745a)

---

### 2. Profit by Category


### Key Observations:
- The **Clothing** category has the highest total profit, exceeding **12,000**. 
- **Electronics** follows, with a profit slightly below Clothing, around **10,000**.
- **Furniture** has the lowest profit among the three categories, approximately **8,000**.

### Managerial Decisions:
- **Resource Allocation**:The manager can identify which category is performing best (Clothing) and consider allocating more resources, such as marketing efforts or inventory, to maximize profits in this area.
- **Strategic Decisions**:Understanding profit distribution can influence strategic decisions regarding product offerings. For instance, if Clothing is consistently performing well, the manager could explore expanding the product line in this category.
- **Identifying Underperformance**:With Furniture showing lower profits, the manager might investigate the reasons for this underperformance. This could involve analyzing market trends, customer preferences, or even pricing strategies.
- **Setting Sales Targets**:The manager can set realistic sales targets based on historical performance data. Knowing the profit levels helps in forecasting and budgeting for the next period.
   
![tải xuống (22)](https://github.com/user-attachments/assets/7849c356-0acf-4403-98b7-e8ba62029548)


---

### 3. Sales Distribution by Payment Mode

### Key Observations:
- **Highest Segment:** The largest portion of sales, **45.6%**, comes from **Cash on Delivery (COD)**, followed by **UPI** at **22.1%**. Other payment methods like debit cards, credit cards, and EMI make up smaller portions, with EMI being the least used at **8.0%**.- **Pattern:** COD is the dominant payment method, indicating that customers prefer paying upon receiving the product. Digital payment options like UPI and debit cards are also widely used, but traditional credit cards and EMI options lag behind.

### Managerial Decisions
- **Optimize Payment Options:** The high COD usage suggests customers might value security in transactions. The manager could consider enhancing COD services and ensuring smooth returns/refund processes.
- **Promote Digital Payments:** Since UPI has strong usage, offering discounts for digital payments could further increase their adoption, lowering handling costs associated with COD.
- **Expand Payment Options:** Encouraging more customers to use credit cards or EMI through incentives (like installment plans or cashbacks) could help increase higher-value purchases.
Understanding payment preferences helps the business enhance customer experience and optimize transaction costs.

![tải xuống (17)](https://github.com/user-attachments/assets/aa099640-616a-4244-92ae-7eedd330ebfe)


---
#### 4.Top 10 Performing Cities by Sales

### Key Observations:
- **Indore** has the highest sales amount, indicating it is the top-performing city.

### Managerial Decisions
- **Resource Allocation:** The manager can allocate more resources, such as marketing efforts or stock, to cities like Indore and Mumbai to maximize revenue.
- **Strategy Development:** Cities with lower sales, like Thiruvananthapuram, might need a revised strategy to boost sales. This could include targeted promotions or understanding local customer preferences.
- **Performance Monitoring:** Regular monitoring can help identify trends over time, such as whether certain cities are improving or declining in performance.
- **Market Expansion:** The manager can consider expanding operations in high-performing cities or investigate potential in lower-performing ones.

![tải xuống (18)](https://github.com/user-attachments/assets/3ef75bb9-c54c-48f8-9323-412bd433279e)

---


## Additional Considerations

- **Consider Customer Preferences**: Tailor marketing strategies based on customer preferences.
- **Evaluate Competition**: Analyze competitors to identify differentiation opportunities.
- **Geographic Insights**: Analyze sales data by state and city to identify regional trends and target specific markets more effectively.
- **Promotional Effectiveness**: Assess the impact of promotions and discounts on sales to refine future marketing campaigns.

## Conclusion
This comprehensive analysis of online sales data has provided valuable insights into customer behavior, product performance, and overall business health. By understanding sales trends, profit margins, and customer preferences, we can make informed decisions to optimize our online sales strategy.By implementing these recommendations, we can effectively leverage our online sales data to drive business growth, enhance customer satisfaction, and maintain a competitive edge in the market.


