# Store Sales Report in Power BI

## **Overview**

This project provides an in-depth analysis of store sales using Power BI. The report visualizes sales trends, product performance, and regional insights, enabling businesses to make data-driven decisions to optimize revenue and growth.

## **Objectives**

- Analyze store-level sales performance and trends.
- Identify top-performing products and regions.
- Provide actionable insights to improve sales strategies and revenue growth.

## **Key Features**

- **Dynamic Dashboards**: Interactive visualizations for exploring sales performance.
- **Product Analysis**: Detailed breakdown of product categories and performance.
- **Regional Sales Insights**: Comparative analysis of sales by region.
- **Trend Analysis**: Visualization of sales patterns over time.

## **Technologies Used**

- **Power BI**: Main tool for data analysis and visualization.
- **Data Sources**: CSV/Excel files or a connected database containing store sales data.
- **DAX (Data Analysis Expressions)**: Used to calculate metrics and KPIs.

## **Dataset Information**

- The dataset includes:
  - Store names and locations.
  - Product categories and sales volumes.
  - Time-series data for sales transactions.

## **Steps to Reproduce**

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/AnalyticJosh/Store-Sales-Report-in-Power-BI.git
   cd Store-Sales-Report-in-Power-BI
   ```

2. **Set Up the Environment**:

   - Download and install Power BI Desktop.

3. **Load the Dataset**:

   - Open the Power BI `.pbix` file.
   - Connect to the dataset provided in the repository.

4. **Explore the Dashboards**:

   - Navigate through the interactive dashboards to analyze insights.
   - Use filters to explore specific regions, products, or time periods.

## **Sample Analysis**

### Revenue Calculation

```DAX
Total Revenue = SUM(Sales[Revenue])
```

### Year-over-Year Growth

```DAX
YoY Growth =
(CALCULATE(SUM(Sales[Revenue]), Date[Year] = "2023") -
CALCULATE(SUM(Sales[Revenue]), Date[Year] = "2022")) /
CALCULATE(SUM(Sales[Revenue]), Date[Year] = "2022")
```

## **Results and Insights**

- Key findings:
  - 020-Men product category accounted for 40% of total sales revenue.
  - New Store experienced the highest year-over-year growth at 30%.
  - Seasonal trends indicate peak sales in Q4.
- Suggested strategies:
  - Focus marketing efforts on New Store.
  - Expand inventory for top-performing products during Q4.

## **Visualizations**

- **Sales by Region**: Heatmap comparing regional performance.
- **Top Products**: Bar chart of best-selling products.
- **Revenue Trends**: Line chart illustrating sales growth over time.
- **KPI Dashboard**: Tiles showing revenue, growth, and top categories.

## **Contributions**

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

## **License**

This project is licensed under the MIT License.

---

For further inquiries or feedback, please contact [Joshua Amusan](mailto\:joshuaanalyst2@gmail.com).

