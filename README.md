# Final-Sales-Dashboard-Assignment-
An interactive Tableau dashboard analyzing US Superstore retail data to identify profit drivers, top-performing products, and regional sales trends. Includes data cleaning documentation.

# 📊 Sample Superstore Data Analysis

## Overview
This project is an exploratory data analysis of the "Sample Superstore" retail dataset. The goal was to build an interactive dashboard in **Tableau** that helps stakeholders identify where profit is being generated and which product categories are driving success.

## 🛠 Tools Used
* **Tableau:** For data visualization and dashboarding.
* **Excel:** For initial data inspection and data cleaning.

## 🔍 The Process & Challenges
One of the key technical challenges in this project was data quality. The raw dataset contained `Sales` and `Profit` columns formatted as string text (due to `$` and `,` symbols).

**The Solution:**
To enable aggregation, I performed data cleaning steps to strip currency symbols and convert the fields into valid numerical data types before building the visualizations.

## 📈 Key Insights
* **Geography:** The Consumer segment in **California** is the largest contributor to overall sales volume.
* **Category Trends:** The **Technology** category yields higher sales per transaction compared to Office Supplies.
* **Profitability:** Using a geographic heatmap, I identified specific underperforming regions that require strategic adjustments.

## 🚧 Reflections & Future Improvements
This project served as a foundational exercise in data granularity. I encountered specific challenges in visualizing "Top 10" rankings due to complex file access and aggregation issues.

While the current dashboard provides a high-level overview, I plan to revisit this dataset to refine the granular ranking visualizations as I advance my skills in Tableau table calculations.

## 🤝 Acknowledgements
Special thanks to **EduLinking Career** and **Dr. Karim Mohammed Rezaul** for the guidance on this assignment.


