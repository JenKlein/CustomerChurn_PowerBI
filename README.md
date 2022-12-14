# Customer Churn Report in PowerBI

In response to a growing demand from various teams wanting to better understand customer churn, I developed a comprehensive Churn report in PowerBI. The report features visualizations that are interactive, self-serve and automated to empower end users to make data-driven decisions. 


## Data Model
I built the data model using the star schema method, which is explained in detail [here](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema). As is mentioned in the link, dimension tables support filtering and grouping, and fact tables support summarization. Fields that occured in many of the tables/SQL-pulls, such as location or product-type, were stored in dimension tables for optimized filtering. 

In the screenshot below, the top row of tables are the dimension tables, and the bottom row of tables are the fact tables. 

![image001](https://user-images.githubusercontent.com/69849998/204644830-e50632b4-6e02-4829-a087-f3eeae22df2a.png)


## Sample Dashboard tab from report
This is the first tab of 7 that gives a high level overview of customer churn activity broken out by different metrics and KPI's. 

**Please note that the data fields/results/labels have been blocked-out for confidentiality purposes.
![ChurnSummaryPage1](https://user-images.githubusercontent.com/69849998/204414424-09e1ec39-3d28-4bfa-a066-93d248191eb5.png)



I built a filter panel to allow users to drill down on various metrics, while maximizing space on the dashboard for visualizations. 

![ChurnSummaryPage1-filter](https://user-images.githubusercontent.com/69849998/204414532-2f370900-d6a2-47f5-98a0-12e2ff3fa69d.png)
