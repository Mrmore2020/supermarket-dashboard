
# Project Title

# Supermarket sales Dashboard

## Problem Statement

This dashboard helps the supermarket to know how total sales trend over time, which branch generates the highest revenue, which product line contributes the most to total sales. It also shows the distribution sales across different customer types. It also helps in identifying the product with the highest profit margin, the day of the week that generate the highest revenue and also how total sales vary by customer type (e.g. member vs. non-member) and gender.
## Software used
•	Excel
•	Power BI
•	SQL
## Key objective of the project.
•	Obtain and show at least 8 key metrics.
•	Which branch generates the highest revenue?
•	Which product line contributes the most to total sales?
•	How does total sales trend over time?
•	What is the distribution of sales across different customer types?
•	Do male or female customers spend more on average?
•	Which product lines have the highest profit margins?
•	Which days of the week generate the highest revenue?
•	How do total sales vary by customer type (e.g., member vs. non-member) and gender?
### Steps followed 

Step 1: Data was collected from Kaggle.com, downloaded in excel spreadsheet.

Step 2: Data cleaning using excel afterwards then converted it to CSV file.

Step 3: Transform the data into Power Query Editor to inspect the data to ensure it is in order and perform any transformation where necessary.

Step 4: To obtain all the metrics, you need to create a calculated columns and measures where necessary.

Step 5: inserted a text box for the title of the visual.

Step 6: In this project, I was expected to generate 7 Key Performance Indicators (KPI)/metrics.

•	Total count as Head Count which is generated using calculated measure i.e. Head Count = count rows (table name) then Ent. And card visual was used.
snapshort of Head Count. img width="1893" height="641" alt="Image" src="https://github.com/user-attachments/assets/ea86f5f1-0c28-4caa-a09a-d29f2d17ea0a" 

•	Total Gross income = sum (table name [Gross Income]) then Ent. And card visual was used. 
snapshort of Gross Income. "1873" height="675" alt="Image" src="https://github.com/user-attachments/assets/5c81dcc6-6615-4284-8f78-2994c92fde34"

•	Total Quantity = sum (table name[Quantity]) then Ent. And card visual was used.

•	Total sales = sum (table name [Total Sales]) then Ent. And card visual was used.

•	Average Unit Price = sum (table name [Unit Price]) then Ent but you will have to change it to average on the fields drop-down. And card visual was used.

•	Profit margin = profit margin = divide (SUM (Supermarket Sales [Gross Income]), SUM (Supermarket Sales [Total Sales]), 0) then Enter. Card visual was also used.

Step 7: which branch generate the highest revenue?

•	Drag and drop Branch to ‘Y’ axis and drag and drop total sales on ‘X’ axis then you sort to descending order. Stacked bar chart was used to represent the chart.
snapshort of the brance with the highest revenue. "1843" height="708" alt="Image" src="https://github.com/user-attachments/assets/10462192-f3b3-4200-b14b-ddbe414dc3fd"

Step 8: which product line contribute the most to total sales?

•	Drag and drop product line on ‘X’ axis and Total Sales on ‘Y’ axis then sort to descending order. Here, the stacked column chart was used to represent the chart.
snapshort of product line that contribute most on total sales. " height="765" alt="Image" src="https://github.com/user-attachments/assets/567524ca-1a30-4d64-8fff-3b67affbdf78"

Step 9: which day of the week generate the highest revenue?

•	Under date column, using DAX to create ‘week day’ which is = Week Days = FORMAT (Supermarket Sales[Date], "DDDD") then Ent. After that, you place your Week Days on ‘X’ axis while Sum of Total Sales is placed on ‘Y’ axis. Cluster column chart was applied here,

snapshort of Day of the week that generates the highest revenue.. height="667" alt="Image" src=" height="716" alt="Image" src="https://github.com/user-attachments/assets/80bff47a-2940-49e7-add4-821aeed65b2b"

•	Click on Donut chart, drag and drop gender on Legend fields and drag and drop Total Sales on values then select average total sales. Donut chart was applied here.
Step 11: which product line has the highest profit margin?

•	Click on table on the visuals and check on product line and then profit margin then sort by ascending order. Table was used to represent this.
Step 12: what is the distribution of sales across different customer type. To achieve that, we have only two customer types. Therefore, we used pie chart to represent our chart by clicking on Total Sales at ‘X’ axis while Customer type on ‘Y’ axis.
snapshort of the dashboard:
 
 img width="1884" height="927" alt="Image" src="https://github.com/user-attachments/assets/e04a5fcf-4f63-41c6-9c67-f7f99f4ecf54" 







