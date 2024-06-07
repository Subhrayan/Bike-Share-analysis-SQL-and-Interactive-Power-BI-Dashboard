# Bike Share analysis: SQL and Interactive Power BI Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiZTUwYjZhMDQtZDEwYS00OTljLTkwMjQtZGVjMmUzZDcwNTliIiwidCI6IjYwODIzNDA4LTBlYjktNGE0Zi04ZTcxLTY2MzcwYThmNjU4NSJ9&pageName=d540311b75d967345475

## Problem Statement

The purpose of the analysis was to generate recommendations on raising prices next year through developing an interactive dashboard that displays KPIs for a Bike sharing service provider to drive informed decision making. The analysis was carried out through hourly revenue analysis and inspecting profit and revenue trends, seasonal revenue and rider demographics. With these different insights the stakeholders can decide whether to raise the price or not and by how much amount. 

The analysis can be further carried out by adding hypothesis test to check statistical significance and machine learning to determine which features contributes the most for determining the price.

## Data Analysis Workflow

```mermaid
graph TD;
    Create a Database-->Develop SQL queries;
    Develop SQL queries-->Connect Power Bi to Database;
    Connect Power Bi to Database-->Build a Dashboard in Power Bi;
    Build a Dashboard in Power Bi-->Answer the Analysis Question;
```

### Steps followed 

- Step 1 : Created a database in Microsoft SQL server
- Step 2 : Developed sql queries to join tables,create columns and selecting relevant data for data analysis 
- Step 3 : Connected Power Bi to database
- Step 4 : Transformed data in Power query for data cleaning
- Step 5 : Utilized DAX to crete new measures like profit margin, revenue per rider
- Step 6 : Builded Interactive dashboard in Power Bi
- Step 7 : Answered the analysis question and included a recommendation
           

 # Dashboard  

 
![Screenshot 2024-06-06 033041](https://github.com/Subhrayan/Bike-Share-analysis-SQL-and-Interactive-Power-BI-Dashboard/assets/154826702/9dd2d191-573a-4aa7-a022-ccfa80dd780b)

# Insights

A single page dashboard was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of riders = 3292679

   Number of riders in 2021 = 1243103

   Number of riders in 2022 = 2049576

  64% increase in demand
           
### [2] Price Increase

Old price(2021) = 3.99
  
  New price(2022) = 4.99

  25% increase in Price
    
Price Elasticity = 64/25 = 2.56

Thus positive price elasticity indicates that if we increase the price, demand will increase while other factors remain constant.

  ### [3] Total Revenue = $15,187,365
  
Total revenue in 2021 = $4,959,981

Total revenue in 2022 = $10,227,384

106% increase in revenue

 ### [4] Total Profit = $10,448,578

 Total profit in 2021 = $3,418,533
 
 Total profit in 2022 = $7,030,045

105% increase in Profit

 ### Class
 
 1.1) 81.81 % registered rider 
 
 1.2) 18.19 % casual rider
 


## Recommended Strategy:


Conservative Increase: Considering the substantial increase last year, a more conservative increase
might be prudent to avoid hitting a price ceiling where demand starts to drop. An increase in the range of
10-15% could test the market's response without risking a significant loss of customers.
Price Setting:

•	If the price in 2022 was $4.99, a 10% increase would make the new price about $5.49.

•	A 15% increase would set the price at approximately $5.74.

Recommended Strategy:

Market Analysis: Conduct further market research to understand customer satisfaction, potential
competitive changes, and the overall economic environment. This can guide whether leaning towards the
lower or higher end of the suggested increase.

Segmented Pricing Strategy: Consider different pricing for casual versus registered users, as they may
have different price sensitivities.

Monitor and Adjust: Implement the new prices but be ready to adjust based on immediate customer
feedback and sales data. Monitoring closely will allow you to fine-tune your pricing strategy without
committing fully to a price that might turn out to be too high.

