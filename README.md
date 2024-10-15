# ONLINE SALES DATA REPORT

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

![image](https://github.com/user-attachments/assets/a5e69e5f-c762-40f5-a457-1b9ad7e1e2ee)


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
- **Payment Mode**: Insights into customer preferences regarding transaction methods.
- **Order Date**: For trend analysis over time.

### Data Cleaning/Processing

Before analysis, the dataset needs to be cleaned to:
- Handle missing values
- Remove duplicates
- Ensure consistent data types
- Address erroneous entries (e.g., negative profits)


## Chart Explanations

### 1. Total Sales by Product Category

The chart depicts total sales for each product category: Clothing, Electronics, and Furniture.

#### Key Observations:
- **Electronics Dominates**:  The Electronics category generated the highest total sales, significantly outperforming Clothing and Furniture. This suggests a strong demand for electronic products.
- **Clothing and Furniture**: While Clothing and Furniture sales are lower than Electronics, they still represent substantial revenue streams. This indicates a consistent demand for these product categories.

#### Managerial Recommendations:
- **Resource Allocation**: Prioritize investment in the Electronics category to capitalize on its strong performance and explore growth opportunities.
- **Product Development**: Focus on developing new electronic products or enhancing existing ones to maintain market leadership.
- **Marketing Strategies**: Tailor marketing efforts to target specific customer segments within each category, emphasizing the unique selling points of products.
- **Pricing Optimization**: Analyze pricing strategies for each category to ensure competitiveness and profitability.

![tải xuống (11)](https://github.com/user-attachments/assets/c3fdecc6-14c0-4796-94d8-eb08e22e07da)

---
### 2. Average Profit by Product Category

The chart shows the average profit by category for three categories: Clothing, Electronics, and Furniture.

#### Key Observations:
- **Highest Profit**: Electronics has the highest average profit, followed by Furniture and then Clothing.

#### Managerial Recommendations:
- **Prioritize product categories**: Focus on promoting and expanding product categories with higher profit margins, such as Electronics.
- **Review underperforming categories**: Investigate the reasons for lower profit margins in Clothing and consider strategies to improve profitability.
- **Identify opportunities**: Look for potential opportunities to increase profit margins in all categories, such as optimizing pricing or cost structures.

![tải xuống (14)](https://github.com/user-attachments/assets/e816bc2a-f693-430f-8231-90928a713164)

---

### Combined Analysis

#### Key Observations:
- **Electronics Dominate**: The Electronics category leads in both total sales and average profit, indicating its strong performance.
- **Clothing's Profitability**: Clothing has moderate sales but lower profit margins compared to Electronics. Focus on improving profitability through cost reduction or pricing strategies.
- **Furniture's Potential**: Furniture has good sales and high profit margins, suggesting potential for growth and increased revenue.

#### Managerial Recommendations
- **Prioritize Electronics**: Invest in marketing, product development, and inventory for Electronics to capitalize on its success.
- **Optimize Clothing**: Analyze cost structure and pricing for Clothing to identify areas for improvement. Consider product mix adjustments or cost-saving measures.
- **Grow Furniture**: Explore strategies to increase sales for Furniture, such as targeted marketing or product expansion.

---

### 3. Quantity Sold by Sub-Category

#### Key Observations:
- **Saree**: The Saree sub-category has the highest quantity sold, indicating strong demand and popularity among customers. This suggests that marketing efforts or seasonal trends may be effectively driving sales.
- **Tables**: In contrast, Tables show the lowest quantity sold, which may suggest a lack of interest, ineffective marketing, or potential issues with product visibility.

#### Managerial Recommendations:
- **Focus on High-Demand Products**: To capitalize on the strong demand for Sarees, management should consider increasing inventory levels to ensure that supply meets the demand, especially during peak sales periods. Additionally, promotional efforts could be intensified to further boost sales.
- **Investigate Poor Performers**: Management should conduct a detailed analysis of the Tables sub-category to understand the reasons behind poor sales.
![tải xuống (13)](https://github.com/user-attachments/assets/ef97a734-34b2-4b2d-9281-c6e66a3187e7)

---

### 4. Average Profit Margin by Sub-Category

This chart analyzes average profit margins across sub-categories.

#### Key Observations:
- **Profitability Variation**: The average profit margin for each sub-category varies significantly. Some sub-categories, like "Printers" and "Trousers," have a positive profit margin, while others, such as "Chairs" and "Electronic Games," have a negative margin.
- **High-Profit Sub-Categories**: "Printers" stand out with the highest average profit margin, followed by "Trousers" and "Accessories." These sub-categories might be generating substantial revenue and contributing positively to the overall profitability.
- **Loss-Making Sub-Categories**: "Chairs" and "Electronic Games" are the primary loss-making sub-categories. These might require closer examination to identify cost-saving measures or pricing adjustments to improve their profitability.

#### Managerial Recommendations:
- **Focus on Profitable Sub-Categories**: The manager can allocate more resources and marketing efforts to sub-categories with high profit margins like "Printers." This could involve increasing inventory, promoting these products, or exploring opportunities to expand their product lines.
- **Address Loss-Making Sub-Categories**: For sub-categories like "Chairs" and "Electronic Games," the manager should investigate the reasons for the losses. This could involve analyzing costs, pricing strategies, or product quality issues. Potential actions might include reducing costs, increasing prices, or discontinuing unprofitable products.
- **Diversification**: The varying profit margins across sub-categories highlight the importance of product diversification. A balanced portfolio can help mitigate risks associated with fluctuations in the profitability of individual sub-categories.
- **Profit Margin Analysis**: Regularly tracking and analyzing profit margins for each sub-category can provide valuable insights into the overall business performance and identify areas for improvement.
![tải xuống (15)](https://github.com/user-attachments/assets/c0ac81d0-7b37-4943-ad16-87cbb2a44778)

---
### Combined Analysis

#### Key Observations:
- **High-Profit, High-Volume Sub-Categories**: "Saree" and "Electronic Games" are driving overall profitability. Focus on maintaining their success and exploring growth opportunities.
- **High-Profit, Low-Volume Sub-Categories**: "Printers" and "Accessories" offer potential for increased revenue with targeted strategies.
- **Loss-Making Sub-Categories**: "Chairs" and "Electronic Games" require urgent attention to address profitability issues.
- **Low-Profit, Low-Volume Sub-Categories**: "Kurti," "Leggings," "Phones," "Shirt," "Skirt," and "Stole" might need evaluation for discontinuation or repositioning.

#### Managerial Recommendations:
- **Prioritize High-Profit Sub-Categories**: Invest in marketing, product development, and inventory for "Saree" and "Electronic Games."
- **Optimize High-Profit, Low-Volume Sub-Categories**: Implement targeted marketing, promotions, or cross-selling for "Printers" and "Accessories."
- **Address Loss-Making Sub-Categories**: Conduct a thorough analysis of costs, pricing, and product quality for "Chairs" and "Electronic Games.".Implement corrective measures or consider discontinuation.
- **Evaluate Low-Profit, Low-Volume Sub-Categories**: Assess the strategic fit of these sub-categories and make informed decisions about their future.

---
### 5. Total Sales by Payment Method

The chart shows total sales amounts for each payment method.

#### Key Observations:
- **Highest Sales**: COD leads in total sales, followed by Credit Card and Debit Card.

#### Managerial Recommendations:
- **Promote Preferred Methods**: Focus on COD as it is the most popular.
- **Explore Additional Options**: Consider incentives for less popular payment methods.
![tải xuống (12)](https://github.com/user-attachments/assets/8fcc793a-8187-47e1-8533-0148f0c3bc82)

---

### 6. Monhthly Sales Trend Over Time

The chart shows the monthly sales trend over time for PV Transpacific.

#### Key Observations:
- **Highest Sales**: The highest sales occurred in October 2018, followed by December 2018 and August 2018.
- **Increasing/Decreasing Pattern**: There is a clear seasonal pattern, with sales increasing from January to October and then decreasing from November to December.
- **Significance: Understanding this seasonal pattern is important for sales forecasting and planning. Managers can anticipate peak sales periods and adjust inventory levels, staffing, and marketing efforts accordingly.

#### Managerial Recommendations:
- **Seasonal Planning**: Prepare for increased sales during peak seasons by ensuring adequate inventory, staffing, and promotional activities.
- **Inventory Optimization**: Reduce inventory levels during off-peak seasons to minimize holding costs.
- **Marketing Campaigns**: Tailor marketing efforts to align with seasonal trends, focusing on promoting products that are in high demand during peak periods.

![tải xuống (20)](https://github.com/user-attachments/assets/0d8c6f26-8715-48b2-88f9-758ba1e236d9)

---

## Additional Considerations

- **Consider Customer Preferences**: Tailor marketing strategies based on customer preferences.
- **Evaluate Competition**: Analyze competitors to identify differentiation opportunities.
- **Geographic Insights**: Analyze sales data by state and city to identify regional trends and target specific markets more effectively.
- **Promotional Effectiveness**: Assess the impact of promotions and discounts on sales to refine future marketing campaigns.

## Conclusion
This comprehensive analysis of online sales data has provided valuable insights into customer behavior, product performance, and overall business health. By understanding sales trends, profit margins, and customer preferences, we can make informed decisions to optimize our online sales strategy.By implementing these recommendations, we can effectively leverage our online sales data to drive business growth, enhance customer satisfaction, and maintain a competitive edge in the market.


