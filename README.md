# Sales-Insight-Power-BI-Dashboard
In the following projects, we are going to be performing an analysis on the performance of Sales at AtliQ Business Hardware Sales, India. I carried out this project by analyzing data from Codebasics AtliQ SQL open source file. MySQL was used to query the data from the database and imported into PowerBI where the actual analysis was carried out.

# Problem Statement
The goal of this analysis is to

Determine the current market demand for products and how it varies by region/location.
Know the current sales performance and how it compares to past performance.
identify the areas where sales performance is lacking or could be improved.
To discover target markets or goods that have the greatest impact on sales success.
Finally, the goal is to create data-driven plans that can aid in increasing sales, improving customer happiness, and driving corporate growth.
Concepts used in this project: 
MySQL (Select, alias, Views)

PowerBI concepts like:

importing data from SQL to PowerBI
creating columns for calculations for dates, time, and duration
Creating key performance indicators (KPIs) and other business calculations,
Developing general DAX calculations that deal with text and numbers,
Performed advanced DAX calculations for solving statistical measures and other mathematical formulas
Data Modelling,
Measures,
filters,
tooltips,
Page buttons,
Data Visualization

You can find a link to get started with installation and restoration of the database to your local machine. here:
Data Transformation:
Several structured queries were written to get the right tables and then saved as views in the Database on SQL Management studio. The tables and views are:
Transactions Table
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/3eee9302-e290-4025-9134-eb01b62bf4da)

Customers Table 
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/b930e695-71ba-4014-b962-bdf4e29ff5f9)

Product Table 
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/aed865fe-f41f-433a-9e90-0fe7320bbded)

Date Table
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/f94959b2-c970-4563-8aca-c23b0c0116b2)

Markets Table 
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/d001a258-ecfa-4341-95b6-5bb5403c1232)


These dataset were then imported into PowerBI desktop for analysis using the step below.
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/b3bec909-30bd-4021-af5c-cfed21e2500c)


Determining correlation between tables
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/4db4c2f8-7e8b-4c7e-9163-1441816d5f7b)


Transforming data in Power Query. This process includes checking for null values, inappropriate data types, difference in formats (in this case, there are few rows where the sales is in USD, unlike the rest of the data which is in INR).
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/fc516bf9-44f1-42ea-b4d0-f3d5fbf479e2)

Writing several Dax and creating measures and calculated columns to get the right metrics for the Sales Performance analysis.
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/e6360fdf-049d-449c-b8de-cbeb6781bf00)

Creating targets in a table named "Profit Target".
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/0612e4a9-ce43-428d-83ec-05f14383abf6)
	
Data Analysis and Visualization
Several expressions and functions were made to arrive at the desired KPI or Metrics.
I arrived at a report with three (3) pages named:

Key Insights
Profit Insights
Detailed Performance

Features of the Report
Key Insights
The first page is Key Insights and it contains information regarding overall revenue and sales performance of AtliQ Business Hardware Sales. In this page, we can see Total Revenue, Total Products Sold, Top Products, and also Revenue Trends from 1 October 2017 to 1 June 2020. this page let viewers know about the overall sales condition on AtliQ Hardware Business.
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/1c5333f9-9d4c-4b0a-818e-57629967fa4e)

Profit Insights
The second page is Profit Insights. It contains information regarding overall profits made and products performance. We can see Profit contribution by Markets, the top and bottom 6 performing products, overall profit margin, and also trends between revenue and profit.
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/945bbda3-6b44-4787-b456-b55e360af368)

Detailed Performance
The last page is Detailed Performance. It contains information regarding the performance of each markets. We can see whether a store is outperforming or underperforming the targeted profit.
![image](https://github.com/AstreNot/Sales-Insight-Power-BI-Dashboard/assets/112799855/89e85f64-bd26-45d9-b89d-37e4b809b1c8)

Results
There is a positive trend of revenue going upwards until July 2018. The trend of revenue then goes downward until October 2020. The sudden decline in February 2020 could be caused by Covid-19 outbreak.

Electricalsara Stores, located in Delhi NCR, has the highest revenue contribution which is 41.97%, followed by Electricalslytical, Located in Mumbai, at 5.04%. Electricalsara Stores is located in Delhi NCR which is the most populated region in India followed by Mumbai. Population variable, in this case, explains a high contribution percentage both stores had.

Product code "Prod329" is the top profit contributor with ₹1.95M total profits, followed by "Prod318" with ₹1.87M total profit. There are also products that have not made any profit which is "Prod073".

The highest profit margin percentage is taken by Surat with a value of 4.86%, higher than Delhi NCR with a value of 2.3%, despite Delhi NCR being the most populated region in India. This could be caused by Surat having the highest per capita income in India, where buyers have little to no attention of whether products is at the original price or not. 

In 2018, the company gains a total Net Profit of 9M and Total Revenue of 414M. While in 2019, the company gains a total Net Profit of 10M and Total Revenue of 336M. There is an increase of 11% in total net profit but a 20% decrease in total revenue. The decreased value in revenue and the increased value of net profit between 2018 and 2019 could be caused by the company efficiency in cutting products cost while maintaining products quality. Thus, AtliQ Business Hardware Sales in 2019 is better than 2018 despite the decrease in revenue.


Recommendation
There are no doubts that the AtliQ Business Hardware net profit is increasing slowly until February 2020. However, there is room for more improvements, especially in cutting production cost for the top 6 highest revenue products in order to increase the company's profit margin.

Granting an appreciation token or benefits for stores that outperform the targeted profit target of 2-3% and slowly increasing the targeted profit. Benefits, like advertising a certain store or upgrading a normal store into a flagship store, will surely motivate stores while also increasing company's own sales.

Use database to gather customer feedback to get their experiences about the product or services. This information can be used to identify areas for improvement.

Making a fresh ad campaign to influence buyers on company's branding, especially in Delhi NCR. This would help increase awareness and loyalty of the products and generate positive word of mouth marketing.

Understand Customers purchasing pattern by carrying out an analysis on this. This will tell what customers are buying, when they are buying and how to promote the goods to the customers.

Thank you for reading.
I am open for entry-level data analyst role. Feel free to contact me!
