Superstore Sales Analysis
Project Overview
This project analyzes the Superstore dataset (9,994 rows, 21 columns, 2015–2018) to uncover actionable insights for marketing and managerial decisions. Using Python (Pandas, Seaborn, Matplotlib) for data cleaning and exploratory data analysis (EDA) and Power BI for interactive visualizations, the project identifies trends in sales, profits, customers, and products. A professional PowerPoint presentation summarizes the findings, making this a portfolio-ready showcase of data analysis and visualization skills.
Objectives

Analyze sales data to identify trends, patterns, and opportunities.
Provide actionable insights for optimizing profitability and business strategies.
Create an interactive Power BI dashboard and a polished PowerPoint report.

Repository Structure
superstore-analysis/
├── superstore_analysis.ipynb      # Python Jupyter Notebook with data cleaning and EDA
├── superstore_dashboard.pbix      # Power BI dashboard file
├── superstore_sales_report.pptx   # PowerPoint presentation (9 slides)
├── superstore_sales_report.pdf    # PDF version of the presentation
├── Sample - Superstore.csv        # Dataset used for analysis
├── visuals/                       # Exported visuals from Python and Power BI
│   ├── profit_histogram.png
│   ├── discount_profit_scatter.png
│   ├── top_products_bar.png
│   ├── correlation_heatmap.png
│   ├── dashboard_screenshot.png
├── README.md                      # Project overview and instructions
├── LICENSE                        # MIT License

Key Insights

Discounts and Profitability: High discounts negatively impact profits, suggesting a need for optimized discount strategies.
Category Performance: Technology (especially Copiers) drives the highest profits; Furniture (Tables, Bookcases) incurs losses.
Regional Trends: West and East regions are the most profitable.
Customer Impact: A small group of key customers contributes significantly to profits.
Seasonal Trends: Sales peak at year-end, indicating seasonal marketing opportunities.
Sales vs. Profit: High sales do not always equate to high profits, warranting pricing or cost reviews.

Tools Used

Python: Pandas for data manipulation, Seaborn and Matplotlib for visualizations.
Power BI: Interactive dashboard with KPIs (Total Sales: $2,297,000, Total Profit: $287,000) and visuals (line charts, pie charts, bar charts, slicers).
PowerPoint: Professional 9-slide presentation summarizing the analysis.

Visuals

Python Visuals (in visuals/):
Histogram of Profit/Sales (right-skewed with outliers).
Scatterplot of Discount vs. Profit (negative correlation).
Bar chart of top 10 products by sales/profit ("Canon imageCLASS 2200 Advanced Copier" leads).
Correlation heatmap (Sales, Profit, Discount, Quantity).


Power BI Visuals (in visuals/ and superstore_sales_report.pptx):
Line chart: Monthly sales trends.
Pie chart: Profit by category.
Donut chart: Profit by segment.
Bar chart: Top products.
Slicers: Interactive filters for Region, Segment, Category.



How to Run

Python Analysis:
Install dependencies: pip install pandas seaborn matplotlib jupyter.
Open superstore_analysis.ipynb in Jupyter Notebook to view or run the analysis.
Dataset: Sample - Superstore.csv (included; if not, source from [Kaggle link]).


Power BI Dashboard:
Open superstore_dashboard.pbix in Power BI Desktop to explore the interactive dashboard.
Screenshots available in visuals/ and superstore_sales_report.pptx.


Presentation:
View superstore_sales_report.pptx or superstore_sales_report.pdf for the summarized report.



License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For questions or access to additional files (e.g., .pbix if not uploaded due to size), contact Mustafa Aoun via [email@example.com] or [LinkedIn profile].

Prepared by Mustafa Oun, June 26, 2025
