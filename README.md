# retail-sales-analysis
"Demonstration of data analysis skills (Python/Pandas) applying ETL, EDA and visualization techniques to analyze an annual sales dataset and generate business recommendations."

This is a project that was simulated with AI, a summary of the data content was given and a request was made to develop problems to be solved, and what the client wanted as the final result.

Problem proposed by AI
Project Steps:
1. Data Preparation and Cleaning (Essential!)
Check Data Types:
Ensure that Date is in datetime format.
Check that Quantity, Unit Value and Final Value are numeric.
Confirm that Sales Code, Store ID and Product are of string/object type.
Handling Missing Values:
Check if there are null values ​​(NaN) in any column. If there are, decide how to handle them (remove the row, fill with a mean/mode value, etc.).
Check Duplicates:
Identify and remove duplicate rows, if they exist (it may be useful to consider Sales Code for this).
2. Exploratory Data Analysis (EDA)
Total Sales:
Calculate the total sales value for the period of one year.
Calculate the total quantity of items sold.
Performance by Store:
Identify the top 5 stores with the highest sales value.
Calculate average sales per store.
Performance by Product:
Identify the top 5 best-selling products in terms of quantity and value.
Calculate gross profit per product (if Final Value already represents revenue, you can consider Final Value per product as "profit" for simplicity, or if you have unit cost, use Final Value - Cost).
Time Analysis:
Aggregate sales by month and by quarter.
Identify the months with the highest and lowest sales volume.
3. Data Visualization
Bar Chart:
Create a bar chart for total sales by store (top 5).
Create a bar chart for total sales by product (top 5).
Line Chart:
Draw a line chart showing the evolution of monthly sales throughout the year.
Other Charts (Optional, but useful):
You can use a scatter plot if you want to analyze the relationship between Quantity and Final Value for example, although for this project, bar and line charts are more crucial.
4. Insights and Conclusions
Based on your analysis and visualizations, answer the following questions:
Which stores performed best?
Which products were the “best sellers”?
Was there any seasonality in sales (peaks in certain months, declines in others)?
What could be the next steps to optimize sales (e.g., focus marketing on underperforming products or invest more in top-performing stores)?
Resolution is in the file (Projeto1vendas.ipynb)
