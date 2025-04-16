# Supermarket Sales Analysis

This repository contains an analysis of supermarket sales data using Python and Matplotlib for visualizations. The goal of this project is to provide insights into supermarket sales through detailed analysis and visualizations, enabling better decision-making based on the data.

## Technologies Used
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating visualizations such as bar charts, pie charts, and line graphs.

## Dataset Overview
The dataset contains **1000** records of sales transactions, with several features, including:
- `Invoice ID`, `Branch`, `City`, `Customer type`, `Gender`, `Product line`, `Unit price`, `Quantity`, `Tax 5%`, `Total`, `Date`, `Time`, `Payment`, and more.

The objective of this analysis is to derive actionable insights related to customer behavior, product performance, and sales trends across different parameters.

## Data Cleaning & Preprocessing

### Handling Missing Data
Upon inspecting the dataset, it was observed that there were **no missing values** across any columns, meaning the data was clean and ready for analysis.

### Data Types
Several columns had inappropriate data types:
- The `Date` and `Time` columns were in string format and were converted to `datetime` format for easier manipulation:
  - `Date` was converted to `datetime` for time-based analysis.
  - `Time` was converted to `datetime`, and the **hour of the transaction** was extracted for hour-based analysis.

### Feature Engineering
- The `Day` of the week was derived from the `Date` column to analyze sales trends across different days of the week.

## Data Visualization
Key visualizations were created using **Matplotlib** to highlight important trends and patterns:
- **Bar Plots**:
  - Total sales by **Branch**.
  - Total sales by **Product line**.
  - Total sales by **Gender**.
- **Pie Charts**:
  - Distribution of **Payment methods** (Cash, E-wallet, Credit Card).
- **Bar Charts**:
  - Sales trends by **Hour of the day**.
  - Sales trends by **Day of the week**.

## Key Insights
1. **Total Revenue**: The supermarket generated a total of **$322,966.75** in revenue.
2. **Branch Performance**: **Branch C** achieved the highest total sales, followed closely by **Branch A** and **Branch B**.
3. **Top Product Lines**: The **Food and Beverages** product line generated the most revenue.
4. **Gender Analysis**: **Female** customers, on average, spent slightly more than **Male** customers.
5. **Peak Sales Hours**: The highest sales were recorded between **7 PM and 8 PM**.
6. **Day of the Week**: **Sales peaked on Saturdays**, indicating a potential trend in shopping behavior.
7. **Payment Methods**: **Cash** and **E-wallet** were the most preferred payment methods, making up **34.4%** and **34.5%** of the total transactions, respectively.

## Conclusion
This analysis provides valuable insights into supermarket sales patterns, customer behavior, and operational trends. The findings could help optimize product offerings, promotional strategies, and customer engagement at different times of the day or week.

## Reference
![Sales Visualization](download (1).png)
