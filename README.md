# E-Commerce Sales Data Analysis

## Project Description

This project focuses on analyzing sales data from an e-commerce company to uncover trends and insights. The analysis spans sales data from January to December 2019. It aims to answer key business questions such as:
- Which month had the highest sales?
- Which states or cities generated the most revenue?
- What are the peak hours for customer purchases?
- What are the most commonly sold product combinations?
- Which products are top sellers?

The insights derived from the analysis can be leveraged to inform business decisions and optimize sales strategies.

---

## Project Walkthrough

### 1. Data Import and Merging
- Sales data from each month of 2019 is imported and merged into a single DataFrame for comprehensive analysis.

### 2. Data Cleaning
- Invalid data and empty rows are removed.
- Columns are correctly typed (e.g., converting **Quantity Ordered** and **Price Each** to integers and floats, respectively).
- The **Purchase Address** column is split into separate columns for **street**, **city**, **state**, and **zip code**.

### 3. Revenue Analysis
- **Total revenue** is calculated for each month.
- The month with the highest and lowest sales is identified.
- Monthly revenue trends are visualized to highlight key sales periods.

### 4. Geographic Sales Analysis
- Total revenue by **city** and **state** is analyzed.
- Visualizations show the distribution of revenue across different cities, helping to identify high-performing regions.

### 5. Peak Purchase Hours
- The **Order Date** is converted to datetime format.
- The number of orders placed during each hour of the day is determined.
- The peak hours for customer purchases are visualized, providing insight into optimal times for marketing efforts.

### 6. Product Combination Analysis
- Orders containing multiple products are identified.
- The most common product combinations purchased together are analyzed, providing valuable insights for cross-selling strategies.

### 7. Product Sales Analysis
- The number of times each product was sold is counted.
- The most sold products are visualized to guide inventory management and promotional efforts.

---

## Key Insights
- Identified the **best and worst performing months** in terms of revenue.
- Recognized **top cities and states** generating the highest sales, which can inform localized marketing efforts.
- Determined **peak hours for customer purchases**, aiding in marketing campaign optimization.
- Found **frequently bought product combinations**, which can be used for cross-selling and bundle offers.
- Highlighted the **most popular products**, which will help guide inventory management and product promotions.

---

## Tools and Technologies

- **Data Processing and Analysis**: Python (Pandas, NumPy)
- **Data Visualization**: Matplotlib, Seaborn
- **Dataset**: E-Commerce sales data for 2019

---

## Usage

This script can be used to perform detailed sales analysis for e-commerce companies. The insights generated can be applied to:
- **Sales Performance Monitoring**: Track monthly revenue and identify trends.
- **Customer Behavior Analysis**: Understand the geographic and temporal patterns of customer purchases.
- **Product Management**: Identify top-performing products and product combinations to guide inventory and promotional strategies.

Feel free to customize and extend this analysis based on your specific business needs or additional data.

---
