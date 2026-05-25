Plant Co. Performance Report
A Power BI report built to track and compare sales performance for a fictional plant company across 2022 to 2024.

What Does This Report Do?
This dashboard lets you see how the company is performing compared to the same time last year. You can switch between Sales, Quantity and Gross Profit using a slicer and the whole report updates automatically.

Tools Used

Power BI Desktop — Built the report and all visuals
Power Query — Cleaned and prepared the data before loading it in
DAX — Written to create measures, calculations and dynamic titles
File Format — .pbix


Where Does the Data Come From?
An Excel file with three tables:

Fact_Sales — All the sales transactions including dates, prices and costs
Dim_Account — Information about each customer account and their country
Dim_Product — Product details like product type, size and family


What's in the Report?
Header Cards at the Top
Shows four key numbers at a glance:

YTD — how much has been sold this year so far
YTD vs PYTD — are we up or down compared to last year shown in red or green
PYTD — what the same period looked like last year
GP% — gross profit percentage

Bottom 10 Treemap
Shows the 10 worst performing countries so you can quickly see where the biggest drops are happening
Waterfall Chart
Shows which months are up or down compared to last year — you can drill down into countries and products to see exactly what is causing the changes
Line and Column Chart
Compares this year vs last year month by month broken down by product type
Scatter Chart
Shows where each account sits in terms of profitability and sales volume — great for spotting accounts that are very profitable but not buying enough

How to Open It

Download the .pbix file
Open it in Power BI Desktop
Use the Values slicer to switch between Sales, Quantity and Gross Profit
Use the Year dropdown to filter by year
Click on any visual to drill down for more detail
