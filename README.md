
## Introduction

Welcome to the Sales Analysis Project! This dataset, sourced from [Samruddhi Bhosale on Kaggle](https://www.kaggle.com), contains two key tables that have been merged into one comprehensive dataset for analysis:

- **Orders.csv**: Contains customer details, including:
  - **Order ID** (Primary Key)
  - **Order Date**
  - **Customer Name**
  - **State**
  - **City**

- **Details.csv**: Contains order details with:
  - **Order ID** (Primary Key)
  - Details of all subsequent orders from Orders.csv

This merged dataset is instrumental for analyzing sales performance, understanding customer preferences, and making informed business decisions.
Order ID	Order Date	CustomerName	State	City	Amount	Profit	Quantity	Category	Sub-Category	PaymentMode
B-26055	10/3/2018	Harivansh	Uttar Pradesh	Mathura	5729	64	14	Furniture	Chairs	EMI
B-26055	10/3/2018	Harivansh	Uttar Pradesh	Mathura	671	114	9	Electronics	Phones	Credit Card
B-26055	10/3/2018	Harivansh	Uttar Pradesh	Mathura	443	11	1	Clothing	Saree	COD
B-26055	10/3/2018	Harivansh	Uttar Pradesh	Mathura	57	7	2	Clothing	Shirt	UPI
B-26055	10/3/2018	Harivansh	Uttar Pradesh	Mathura	227	48	5	Clothing	Stole	COD
B-26055	10/3/2018	Harivansh	Uttar Pradesh	Mathura	213	4	14	Clothing	Shirt	COD
B-26055	10/3/2018	Harivansh	Uttar Pradesh	Mathura	94	27	2	Clothing	T-shirt	COD
B-26055	10/3/2018	Harivansh	Uttar Pradesh	Mathura	1250	-12	2	Electronics	Printers	EMI
B-26055	10/3/2018	Harivansh	Uttar Pradesh	Mathura	1218	-420	8	Furniture	Bookcases	COD
![image](https://github.com/user-attachments/assets/a5e69e5f-c762-40f5-a457-1b9ad7e1e2ee)

## Data Discussion

The dataset consists of the following columns:

- **Order ID**: A unique identifier for each transaction.
- **Amount**: The total monetary value of the order.
- **Profit**: The profit earned from the order.
- **Quantity**: The number of items sold in the order.
- **Category**: General classification of the product (e.g., Electronics, Furniture, Clothing).
- **Sub-Category**: A more specific classification (e.g., Phones, Chairs, Trousers).
- **Payment Mode**: The method of payment used (e.g., COD, Credit Card, UPI).

### Important Columns for Analysis

- **Amount** and **Profit**: Critical for understanding financial performance.
- **Quantity**: Helps gauge product demand.
- **Category** and **Sub-Category**: Essential for market segmentation analysis.
- **Payment Mode**: Insights into customer preferences regarding transaction methods.

### Data Cleaning/Processing

Before analysis, the dataset needs to be cleaned to:
- Handle missing values
- Remove duplicates
- Ensure consistent data types
- Address erroneous entries (e.g., negative profits)

```python
df.describe()
```

## Chart Explanations

### 1. Total Sales by Product Category

The chart depicts total sales for each product category: Clothing, Electronics, and Furniture.

#### Key Observations:
- **Electronics Dominates**: The Electronics category generated the highest total sales, indicating strong demand.
- **Clothing and Furniture**: These categories show substantial revenue streams, suggesting consistent demand.

#### Implications for Business Decisions:
- **Resource Allocation**: Prioritize investment in the Electronics category.
- **Product Development**: Focus on enhancing electronic products.
- **Marketing Strategies**: Tailor efforts to target specific customer segments.

![tải xuống (11)](https://github.com/user-attachments/assets/c3fdecc6-14c0-4796-94d8-eb08e22e07da)

---
### 2. Average Profit by Product Category

This chart illustrates average profit for each product category.

#### Key Observations:
- **Electronics Lead in Profitability**: Electronics surpass Clothing and Furniture, indicating higher profit margins.
- **Clothing and Furniture**: These categories may require cost analysis to improve profitability.

#### Implications for Business Decisions:
- **Prioritize Electronics**: Invest in high-margin products.
- **Optimize Clothing and Furniture**: Analyze cost structures to enhance profitability.

![tải xuống (14)](https://github.com/user-attachments/assets/e816bc2a-f693-430f-8231-90928a713164)

---

### Combined Analysis

####Key Insights
- **Electronics Dominate: The Electronics category leads in both total sales and average profit, indicating its strong performance.
- **Clothing's Profitability: Clothing has moderate sales but lower profit margins compared to Electronics. Focus on improving profitability through cost reduction or pricing strategies.
- **Furniture's Potential: Furniture has good sales and high profit margins, suggesting potential for growth and increased revenue.

####Managerial Recommendations
- **Prioritize Electronics: Invest in marketing, product development, and inventory for Electronics to capitalize on its success.
- **Optimize Clothing: Analyze cost structure and pricing for Clothing to identify areas for improvement. Consider product mix adjustments or cost-saving measures.
- **Grow Furniture: Explore strategies to increase sales for Furniture, such as targeted marketing or product expansion.

---

### 3. Quantity Sold by Sub-Category

The chart shows the quantity sold for each sub-category, revealing sales trends.

#### Key Observations:
- **Saree**: Highest quantity sold, indicating strong demand.
- **Tables**: Lowest quantity sold, suggesting a need for investigation.

#### Managerial Implications:
- **Focus on High-Demand Products**: Increase inventory for high-selling items like Sarees.
- **Investigate Poor Performers**: Analyze why Tables are selling poorly and take corrective actions.
![tải xuống (13)](https://github.com/user-attachments/assets/ef97a734-34b2-4b2d-9281-c6e66a3187e7)

---

### 4. Average Profit Margin by Sub-Category

This chart analyzes average profit margins across sub-categories.

#### Key Observations:
- **Profitability Variation**: Sub-categories like **Printers** have high margins, while **Chairs** show negative margins.
- **No Clear Pattern**: There’s no correlation between quantity sold and profit margin.

#### Managerial Implications:
- **Focus on Profitable Sub-Categories**: Allocate resources to high-margin items.
- **Address Loss-Making Sub-Categories**: Investigate costs and pricing for items with negative margins.
![tải xuống (15)](https://github.com/user-attachments/assets/c0ac81d0-7b37-4943-ad16-87cbb2a44778)

---
### Combined Analysis

####Key Insights
- **High-Profit, High-Volume Sub-Categories: "Saree" and "Electronic Games" are driving overall profitability. Focus on maintaining their success and exploring growth opportunities.
- **High-Profit, Low-Volume Sub-Categories: "Printers" and "Accessories" offer potential for increased revenue with targeted strategies.
- **Loss-Making Sub-Categories: "Chairs" and "Electronic Games" require urgent attention to address profitability issues.
- **Low-Profit, Low-Volume Sub-Categories: "Kurti," "Leggings," "Phones," "Shirt," "Skirt," and "Stole" might need evaluation for discontinuation or repositioning.

####Managerial Recommendations
- **Prioritize High-Profit Sub-Categories: Invest in marketing, product development, and inventory for "Saree" and "Electronic Games."
- **Optimize High-Profit, Low-Volume Sub-Categories: Implement targeted marketing, promotions, or cross-selling for "Printers" and "Accessories."
- **Address Loss-Making Sub-Categories: Conduct a thorough analysis of costs, pricing, and product quality for "Chairs" and "Electronic Games." - **Implement corrective measures or consider discontinuation.
- **Evaluate Low-Profit, Low-Volume Sub-Categories: Assess the strategic fit of these sub-categories and make informed decisions about their future.

---
### 5. Total Sales by Payment Method

The chart shows total sales amounts for each payment method.

#### Key Observations:
- **Highest Sales**: COD leads in total sales, followed by Credit Card and Debit Card.

#### Management Decisions:
- **Promote Preferred Methods**: Focus on COD as it is the most popular.
- **Explore Additional Options**: Consider incentives for less popular payment methods.
![tải xuống (12)](https://github.com/user-attachments/assets/8fcc793a-8187-47e1-8533-0148f0c3bc82)

---

### 6. Monhthly Sales Trend Over Time

The chart shows the monthly sales trend over time for PV Transpacific.

#### Key Observations:
- **Highest Sales**: The highest sales occurred in October 2018, followed by December 2018 and August 2018.
- **Increasing/Decreasing Pattern: There is a clear seasonal pattern, with sales increasing from January to October and then decreasing from November to December.
- **Significance: Understanding this seasonal pattern is important for sales forecasting and planning. Managers can anticipate peak sales periods and adjust inventory levels, staffing, and marketing efforts accordingly.

#### Management Decisions:
- **Seasonal Planning: Prepare for increased sales during peak seasons by ensuring adequate inventory, staffing, and promotional activities.
- **Inventory Optimization: Reduce inventory levels during off-peak seasons to minimize holding costs.
- **Marketing Campaigns: Tailor marketing efforts to align with seasonal trends, focusing on promoting products that are in high demand during peak periods.

![tải xuống (20)](https://github.com/user-attachments/assets/0d8c6f26-8715-48b2-88f9-758ba1e236d9)

---

## Additional Considerations

- **Analyze Trends Over Time**: Track changes in sales, profit margins, and product demand.
- **Consider Customer Preferences**: Tailor marketing strategies based on customer preferences.
- **Evaluate Competition**: Analyze competitors to identify differentiation opportunities.

## Conclusion

The analysis of this sales dataset provides valuable insights into the performance of various categories over time. By understanding sales trends and profit margins, management can make informed decisions regarding inventory management, marketing strategies, and customer engagement initiatives. Further analysis could include customer segmentation and payment method preferences to enhance sales strategies.

---

Thank you for your interest in this project! For any questions or contributions, feel free to reach out.
