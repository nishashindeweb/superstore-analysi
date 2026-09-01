# Superstore Sales Analysis

![Dashboard](dashboard2.png)

*Problem:* Order Date had mixed formats - 11/26/2015 + Excel serial 42593 + Errors

*Solution:* Power Query M code -> try Date.From() otherwise Date.AddDays(#date(1899,12,30), Number.From())

*Key Insights:*
- Top 10 Profitable Products
- Category wise Profit Analysis  
- Monthly Sales Trend

*Tools:* Power BI | Power Query | Python (Pandas)

### Other Views
![View 2](dashboard3.png)
![View 3](dashboard4.png)
