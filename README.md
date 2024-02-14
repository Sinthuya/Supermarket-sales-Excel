# Supermarket_sales

### Project overview
This data analysis project aims to analyse the historical sales data of a supermarket company with three different branches for three months. I have used Microsoft Excel to complete this project.

### Data sources
Kaggle: https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales

### Tools
- Microsoft Excel - data cleaning, analysis and visualisation

### Data preparation - cleaning and formatting
I took the following steps:
- converted the data into a table with columns that has filters.
- Inserted dollar sign for the data in the columns unit price, Total, Cogs. Tax and Gross income to indicate money value.
- Inserted percentage sign for the Gross margin percentage column
- Created a new column for Rating and deleted the original column to make the rating a single number. I used the =FLOOR(Q2,1) formula.

### Descriptive statistics analysis

![image](https://github.com/Sinthuya/Supermarket-sales-Excel/assets/150496788/7773f526-ccf4-4cf0-93b5-95f60586fee7)

##### Unit Price:
- Average Unit Price: The average unit price across all stores is $55.67.
- Minimum and Maximum Unit Price: The minimum unit price is $10.08, and the maximum unit price is $99.96.
- Standard Deviation: The standard deviation of unit prices indicates a variation of approximately $26.49 from the mean.
Understanding the distribution of unit prices can help the supermarket in pricing strategies, product positioning, and identifying potential pricing gaps in the market.

##### Quantity:
- Average Quantity Ordered: On average, each transaction involves a quantity of 5.51 items. 
- Variability in Quantity Ordered: The standard deviation of quantity ordered is about 2.92, suggesting some variability in the quantity of items per transaction.
Analysing quantity ordered provides insights into customer purchasing behaviour, inventory management and demand forecasting enabling the company to optimise stock levels and improve supply chain efficiency.

##### Total Sales:
- Total Sales: The combined total sales for all stores amount to $322,966.75.
- Average Total Sales: The average total sales per transaction are approximately $322.97.
- Sales Distribution: The range of total sales is $15,379.37, with a minimum value of $10.08 and a maximum of $99.96.
Monitoring total sales helps the company track revenue, identify high-performing products and assess overall business growth and profitability.

##### Gross Income:
- Average Gross Income: The average gross income across all stores is $15.38.
- Distribution of Gross Income: The standard deviation in gross income is about $11.71, indicating variability in the income generated.
Analysing gross income provides insights into profit margins and the effectiveness of pricing and promotional strategies which enables the company to optimise profitability.

These insights provide a comprehensive overview of the key metrics, helping to understand the distribution and patterns in the data. The variability metrics (standard deviation) indicate the extent of dispersion around the mean values, providing valuable insights into the overall performance across all three stores.

### Top Sales by Product Category Analysis

![image](https://github.com/Sinthuya/Supermarket-sales-Excel/assets/150496788/eedd3ce5-96b3-400b-8cc6-06ecb74bbb11)

The results of this analysis provide an overview of the contribution of sales from each product category to the overall total sales. Food and beverages emerge as the highest-selling category closely followed by others. This analysis helps the company focus on marketing efforts and allocate resources effectively.

### Top sales by branch analysis

![image](https://github.com/Sinthuya/Supermarket-sales-Excel/assets/150496788/80ad378e-e5a5-4da0-bd92-7c952743cefb)

The analysis of total sales by branch provides insights into the performance of each branch within the supermarket. Branch C stands out as the leading contributor to total sales, indicating its significance in the supermarket's revenue generation. This analysis helps to evaluate the effectiveness of each location, allocate resources efficiently and identify opportunities for expansion or improvement in underperforming branches.

### Customer analysis

This Customer analysis provide a comprehensive view of the customer base and their satisfaction levels, guiding strategic decisions for improved customer experience and business growth.
Members (50.1%) constituted for just over half of the of the customer base compared to non-members (49.9%). Gender distribution was equal among males and females. The average customer rating across all sales is 7/10. The majority of customers seem to be satisfied, as reflected in the average rating. 20% of the rating was 7/10, closely followed by 17% for 9/10 and 16% for 6/10.
This analysis helps the business to tailor marketing strategies, enhance customer experiences, and build stronger relationships with customers, ultimately leading to increased loyalty.

![image](https://github.com/Sinthuya/Supermarket-sales-Excel/assets/150496788/fdeabb48-18fc-476c-8cd2-f604cc259cc8)

In conclusion, the analysis of the supermarket sales data emphasises the significance of understanding sales distribution, branch performance, and customer satisfaction for strategic decision-making. The dominance of certain product categories, particularly Food and beverages, emphasises targeted marketing opportunities. Branch C's significant contribution underscores the need for branch-level performance evaluation. Moreover, high customer satisfaction levels and gender parity among members and non-members emphasise the importance of maintaining exceptional customer experiences. Leveraging these insights can drive sales growth, operational efficiency, and customer loyalty, ensuring sustained competitiveness in the retail sector.
