# Sales and Profit Analysis

This project involves analyzing sales and profit data for a retail store to uncover key insights and trends. The analysis is aimed at identifying the performance of product categories, sub-categories, and customer segments while determining the sales-to-profit ratio.

---

## Objectives

1. **Monthly Sales Analysis**:
   - Calculate the monthly sales and identify the months with the highest and lowest sales.

2. **Category Sales Analysis**:
   - Analyze sales based on product categories and identify the highest and lowest-performing categories.

3. **Sub-Category Sales Analysis**:
   - Dive deeper into sub-categories to evaluate their individual performance.

4. **Monthly Profit Analysis**:
   - Calculate the monthly profit and determine the month with the highest profit.

5. **Profit Analysis by Category and Sub-Category**:
   - Evaluate profitability across product categories and sub-categories.

6. **Customer Segment Analysis**:
   - Analyze sales and profit based on different customer segments to understand their contribution.

7. **Sales-to-Profit Ratio**:
   - Calculate the ratio of sales to profit to evaluate the store's profitability.

---

## Key Questions Addressed

1. What is the monthly sales trend, and which months had the highest and lowest sales?
2. Which product categories are generating the highest and lowest sales?
3. How do sub-categories contribute to overall sales and profit?
4. What is the monthly profit trend, and which month had the highest profit?
5. Which product categories and sub-categories have the highest and lowest profit?
6. How do customer segments influence sales and profitability?
7. What is the store's overall sales-to-profit ratio?

---

## Dataset

### Description
The dataset contains transaction-level details of sales and profit from a retail store.

### Key Columns:
- `Order ID`: Unique identifier for each order.
- `Order Date`: Date the order was placed.
- `Product Category`: Broad category of the product (e.g., Furniture, Office Supplies).
- `Sub-Category`: Specific sub-category of the product (e.g., Chairs, Binders).
- `Sales`: Sales amount for the product.
- `Profit`: Profit generated for the product.
- `Customer Segment`: Segment of the customer (e.g., Consumer, Corporate).

---

## Tools and Technologies

- **Python Libraries**:
  - **Pandas**: For data manipulation and analysis.
  - **NumPy**: For numerical operations.
  - **Plotly**: For interactive data visualization.
- **Excel**:
  - For basic data wrangling and reporting.
- **SQL**:
  - For querying and summarizing data.

---

## Steps in Analysis

1. **Data Cleaning**:
   - Remove duplicate rows.
   - Handle missing values.
   - Ensure proper formatting of date columns.

2. **Monthly Sales Analysis**:
   - Aggregate sales by month.
   - Visualize the monthly sales trend using Plotly line charts.

3. **Category and Sub-Category Analysis**:
   - Group sales and profit by categories and sub-categories.
   - Visualize performance using Plotly bar and pie charts.

4. **Profit Analysis**:
   - Calculate monthly profit and identify trends.
   - Analyze profit across categories, sub-categories, and customer segments.

5. **Customer Segment Analysis**:
   - Group sales and profit by customer segments.
   - Compare segment-wise performance using interactive charts.

6. **Sales-to-Profit Ratio**:
   - Calculate the ratio of profit to sales for the overall store and individual categories.

---

## Insights (Examples)

1. **Monthly Sales**:
   - December recorded the highest sales, while February had the lowest sales.

2. **Category and Sub-Category Performance**:
   - Office Supplies is the top-performing category, with Binders being the most profitable sub-category.
   - Furniture has the lowest sales, and Tables underperformed in profit.

3. **Profit Trends**:
   - The store achieved the highest profit in November.
   - Technology products generate a high profit margin compared to other categories.

4. **Customer Segment**:
   - The Consumer segment contributes the most to both sales and profit.
   - Corporate customers have the highest average order value.

5. **Sales-to-Profit Ratio**:
   - The overall sales-to-profit ratio is 1:0.15, indicating a 15% profit margin.

---

## Visualizations

1. **Monthly Sales and Profit Trends**:
   - Interactive line chart using Plotly.
2. **Category and Sub-Category Analysis**:
   - Bar chart of sales and profit by category and sub-category using Plotly.
3. **Customer Segment Performance**:
   - Pie chart showing the contribution of each customer segment.
4. **Sales-to-Profit Ratio**:
   - Scatter plot visualizing the relationship between sales and profit.

---

## Recommendations

1. **Boosting Low-Performing Months**:
   - Launch promotions in low-performing months like February to boost sales.

2. **Optimizing Categories**:
   - Focus on improving Furniture sales by offering discounts or bundling products.

3. **Improving Sub-Categories**:
   - Analyze underperforming sub-categories and explore reasons for low sales.

4. **Targeting Customer Segments**:
   - Design exclusive campaigns for Corporate customers to increase their order volume.

5. **Enhancing Profit Margins**:
   - Identify high sales but low-profit products and optimize their pricing.

---

## How to Run the Analysis

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/jaikumar2406/E-Commerce-Website-Data-Analysis.git
   cd sales-profit-analysis
