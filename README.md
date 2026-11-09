# decathlon-retail-sales
Most dashboards tell you what happened. This time I built one that shows how it performed as compared  to previous year year by utilizing time Intelligence functions in Power BI. 
The headline: net sales were up 24% year over year, with a 39.3% gross margin. But the story I enjoyed digging into was why.

These are the steps I took:
Cleaned the data in Power Query: 240 products, 30 stores, 20 states
Created a Date table, built a star schema, with sales at the center and product, store and date tables around it
Wrote the DAX for Net Sales, Profit, Margin, Units, Orders and AOV, each with YTD, prior-year YTD and YoY%

Designed visuals around questions, not just charts: Which sports and brands carry the business? Where does revenue come from? Which products sell a lot and earn healthy margins?
The plot twist: the hardest part wasn’t the charts, it was making the year-over-year comparison fair. Comparing a full year to a partial year gives you nonsense. 

I wrote the DAX so every KPI is measured against the exact same cutoff date last year. Small detail, big difference in trust.
I also added slicers and a reset button, so anyone can slice the data by state, city, sport, tier or payment method and find their own answers.
It is just so powerful what Power BI can do.
