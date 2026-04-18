Multi-Branch Sales Target vs Achievement Dashboard

An interactive Power BI dashboard designed to analyze sales performance across multiple branches, regions, and sales representatives.

This project compares actual sales with target sales and provides key performance indicators such as Total Sales, Total Sales Target, Achievement Percentage, and Variance. It helps identify high-performing and underperforming regions, branches, and sales representatives through clear and interactive visualizations.

Key Features

- KPI cards for Total Sales, Total Target, Achievement %, and Variance
- Region-wise and branch-wise sales comparison
- Monthly sales trend analysis
- Sales representative performance tracking
- Product category contribution using a donut chart
- Interactive slicers for Month, Region, and Sales Representative
- Detailed performance table for deeper analysis

Tools & Technologies

- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Excel / CSV Dataset

DAX Measures Used

Total Sales = SUM(Sales[Actual Sales])

Total Target = SUM(Sales[Target Sales])

Achievement % = DIVIDE([Total Sales], [Total Target], 0) * 100

Variance = [Total Sales] - [Total Target]

Dashboard Preview

Add your dashboard screenshot here

Objective

The objective of this project is to monitor sales performance, compare targets with actual results, identify performance gaps, and support data-driven decision-making.

Conclusion

This dashboard transforms raw sales data into meaningful insights, making it easier to track performance, identify underperforming areas, and improve overall sales efficiency.
