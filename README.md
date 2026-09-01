# Superstore Sales Analysis

### Problem: Order Date had mixed formats (Excel serial 42593 + MM/DD/YYYY) + Errors
### Solution: Used Power Query M code try Date.From() otherwise Date.AddDays(#date(1899,12,30), ...) 

*Dashboard Insights:*
- Top 10 Profitable Products
- Category wise Profit
- Monthly Sales Trend

*Tools:* Power BI | Power Query | Python
