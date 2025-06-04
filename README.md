# Amazon Sales Analytics Dashboard

## Project Overview

This is a comprehensive Power BI project that I developed to visualize and analyze Amazon sales performance across multiple years, product categories, and U.S. states. The dashboard provides clear, insightful, and actionable information for understanding business performance at a glance.

The project is designed for business users, analysts, and decision-makers who want to track how different regions and categories are performing over time. With interactive filters and visuals, this dashboard helps drive strategic decisions using real sales data, transforming complex datasets into easily digestible visual insights.

## 🔗 Live Dashboard
**[View Interactive Dashboard](https://app.fabric.microsoft.com/view?r=eyJrIjoiMTJiZGI1N2QtMDBmMy00NDI1LThiMDAtZDc3MWM0YzhiODZiIiwidCI6IjY3OWY5YTYyLTIwODQtNGI0Yy1iNzk2LWI1NGFkZTM5ZmUxYiJ9)**

Click the link above to explore the live, interactive version of this dashboard. You can filter data by year, interact with visualizations, and gain real-time insights from the Amazon sales data.

## Features

### Key Performance Indicators (KPIs)
KPIs are displayed prominently, showing:
- **Order Count** – the total number of orders placed
- **Total Sales** – total revenue generated from all orders
- **Total Profit** – the net earnings after subtracting costs

### Time-Series Analysis
A time-series line chart visualizes sales trends on a daily level across selected years:
- Helps detect sales peaks and dips
- Useful for identifying seasonal patterns or campaign effectiveness

### Product Category Breakdown
A treemap chart shows total sales broken down by product categories:
- Visually highlights which categories contribute most to revenue
- Larger boxes indicate higher sales share

### State-wise Profit Analysis
A horizontal bar chart shows profit by U.S. state:
- Quickly identifies high-performing and low-performing states
- Red bars represent states with losses, green bars indicate profit

### Sales Performance Gauge
A sales gauge (or speedometer chart) shows progress toward a sales goal:
- Useful for comparing current performance to a benchmark

### Interactive Filtering
A year slicer allows users to select a specific year from 2011 to 2014:
- Dynamically filters all visuals to focus on that year's data

## Project Structure

The project folder contains all necessary files:

```
├── Amazon_Sales_Analytics.pbix     # The main Power BI dashboard file with all visuals and logic
├── README.md                       # This documentation file, explaining the project purpose and structure
├── dashboard_screenshot.png        # A screenshot image showing the full dashboard layout
└── data/
    └── Amazon_Sales_Data.csv      # The raw dataset used in the dashboard, containing order-level details
```

## Dashboard KPIs

### Order Count
- Reflects the number of individual transactions completed
- Indicates the level of customer activity

### Total Sales
- The total value of products sold
- Represents gross revenue, before deducting costs

### Total Profit
- The remaining amount after deducting costs from total sales
- A key indicator of business efficiency and financial health

## Key Insights from the Dashboard

- **California** leads in profit generation across all years, making it the top-performing state
- States like **Colorado**, **Oregon**, and **Arizona** consistently report losses, indicating potential issues in cost management or demand
- **Chairs**, **Phones**, and **Tables** are the top-selling product categories. These can be prioritized for promotions or inventory management
- Time-series trends show periodic spikes in sales, likely due to festive seasons or marketing campaigns
- The year-wise slicer allows stakeholders to analyze trends specific to a chosen year and compare performance over time

## Tools and Technologies Used

### Power BI Desktop
Used to build the dashboard, load and transform data, and create visualizations

### DAX (Data Analysis Expressions)
Used to calculate dynamic measures like total profit and custom KPIs

### CSV (Comma-Separated Values)
The raw data source format used to feed into Power BI

### Git and GitHub
Used for version control and collaborative sharing of the project

## Conclusion

This project showcases how business intelligence tools like Power BI can transform raw sales data into visually compelling insights. It helps businesses understand what's working, what's not, and where to focus for better profitability and performance.

The dashboard is fully interactive, user-friendly, and adaptable, and it serves as a valuable asset for retail or e-commerce analytics.
