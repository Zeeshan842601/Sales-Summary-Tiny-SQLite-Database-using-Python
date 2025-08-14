# Sales-Summary-Tiny-SQLite-Database-using-Python
Python script connects to SQLite DB (sales_data.db) to fetch and summarize sales data. Calculates total quantity and revenue per product (2 decimal precision) using SQL, displays results via pandas, and plots revenue bar chart with matplotlib. Chart saved as sales_chart.png.

This project connects a Python script to a small SQLite database (sales_data.db) to fetch and summarize sales data.
The script:

Connects to sales_data.db using sqlite3.

Runs SQL queries to calculate total quantity sold and total revenue per product (rounded to 2 decimals).

Displays results in the console using pandas.

Plots a simple bar chart of revenue by product with matplotlib.

Saves the chart as sales_chart.png.
