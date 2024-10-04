# Credit-Card-Sales-Report


Project Summary: Developed an interactive Power BI dashboard to analyze credit card sales data, providing key insights into sales performance, customer behavior, and revenue trends. The dashboard facilitated data-driven decision-making for stakeholders and improved the sales strategy.

Key Responsibilities:

Designed and implemented data models in Power BI, integrating credit card sales data from multiple sources.
Utilized DAX (Data Analysis Expressions) functions to create custom metrics, including revenue percentage, monthly performance, average transaction value, and customer segmentation.
Created visualizations such as bar charts, line charts, and KPIs to illustrate sales trends, top-performing products, customer segments, and regional performance.
Built dynamic slicers and filters to allow users to interact with the report and drill down into specific categories, time periods, or regions.
DAX Functions Used:

CALCULATE(): To create dynamic calculations for revenue growth based on different filters such as product category, region, and customer segment.
SUMX(): To calculate total sales per customer and product, aiding in customer behavior analysis.
QUARTER(),MONTH(),WEEKNUM(),DAY(): Used to extract quarter,month,week number, day from the dates given for analysing trends in different categories.
FILTER(): Applied to isolate specific subsets of data for in-depth analysis of customer segments.
RANKX(): Used to rank products and customers based on sales volume.
IF(): For conditional analysis to flag high- and low-performing regions.
AVERAGE() : To calculate average acquisition cost.
ALL() : Used in calculating segment wise percentage sales.

Tools & Technologies:

Power BI for data visualization and reporting.
SQL for querying and data extraction.
Excel for preliminary data cleaning and analysis.
**

Key Insights :
1.	The analysis revealed that BLUE card category accounted for 85% of the total revenue followed by Silver (9%), Gold (4%) and Platinum (2%) categories. 
2.	The average acquisition cost is maximum for PLATINUM (Rs 98.06) card category followed by Blue (Rs 96.40), Silver (Rs 95.40) and Gold (Rs 93.71).  
Interestingly, PLATINUM Card Category is responsible for minimum revenue and maximum acquisition cost.
3.	The analysis of customers belonging to different income groups further revealed that 82% of customers belonging to high income group opted for BLUE Cards, 11 % opted for Silver Cards, 5% opted for Gold Cards and a mere 2% opted for Platinum Cards 
4.	Customers belonging to high income group accounted for 48% of total revenue but only 30% of the total cards sold have been sold to these high income group customers.
5.	The maximum average credit limit is given to high income group customers followed by low income group customers and medium income group customers.
6.	Onboarding of new customers is lowest in the months of March, September and November.


Recommendations :
1.	It is advisable to discontinue Platinum Card Category since it is responsible for maximum acquisition cost and minimum revenue. More focus should be on BLUE cards only and efforts to be made to make these cards the best in the market.
2.	Number of cards sold to high income group customers are less as compared to other two. Since these customers are responsible for maximum revenue, more efforts should be made to onboard high income group customers. 
3.	Credit limit offered to medium income group customers is the lowest. Ideally it should be higher than that offered to low income group customers. This seems like an anomaly and should be looked into on priority to increase interest income from these categories of customers.
4.	Special offers can be given to increase onboarding of new customers for the months which are responsible for lower onboarding like March, September, November. 



