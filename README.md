# Telecom Customer Churn Analysis
**Tool:** Power BI  |  **Database:** SQL Server  |  **Rows:** 7,043 customers

## Dashboard Preview
(telecom-churn-analysis/dashboard/images/overview.png)

## Project Overview
Analysis of telecom customer churn to identify key drivers,
revenue impact, and actionable retention strategies.

## Key Findings
- **Churn Rate:** 26.54% — above industry average of 15–25%
- **Net Customer Growth:** -1K — company losing more than gaining
- **Revenue Lost to Churn:** $3.68M (20.8% of total revenue)
- **Top Churn Reason:** Competitor pressure — 33.39% of all churn
- **Strongest Predictor:** Contract type — churned avg score 1.14
- **Fiber Optic** generates 58% of all internet revenue ($12.41M)
  - **Two Year contracts** worth 2.8x more per customer than Month-to-Month

## Strategic Recommendations
1. Improve device portfolio — 33% of churn is competitor-driven
2. Convert 3,600 Month-to-Month customers to annual contracts
3. Customer service training — 11.77% churn from staff attitude
4. Protect Fiber Optic customers — 58% of all revenue
5. Retention outreach at months 6, 12 and 18 for at-risk profiles

## Analysis Questions Answered
1.How Many customers joined the company during the last quarter?How many customers joined? 454 customers(6.45%)
2.What is the customer profile for a customer that churned,joined and stayed?Are they different?
3.What seem to be the key drivers of custome churn?Competitors are the biggest driver by approximately 33.39%
4.Is the company losing high value customers?If so,how can they retain them?"The company is disproportionately losing high-value Fiber Optic and Month-to-Month customers — representing $3M and $2.5M in churned revenue respectively — while lower-tier DSL and Cable segments remain relatively stable
5.What is the financial impact of churn on the business — and what would a 20% retention improvement mean?Churn has cost the company $3.68M in lifetime revenue and $0.14M every single month in lost recurring charges. This represents a 20.8% revenue drain — meaning for every $5 earned, $1 is lost to churn. If the company retained just 20% of churned customers through a targeted campaign, it would recover approximately $27K per month in recurring revenue without acquiring a single new customer. Given that acquiring a new customer costs 5–7x more than retaining an existing one, a retention-first strategy delivers significantly higher ROI than increasing the acquisition budget
6.Which contract type poses the greatest churn risk — and what does the revenue data reveal about the cost of that risk?Month-to-Month contracts represent the greatest structural churn risk. By customer count, 3,600 customers — more than half the entire base — are on Month-to-Month, meaning over half the company's customers can leave any given month with no financial penalty. By revenue, Month-to-Month churners account for $2.5M in lost lifetime revenue compared to only $0.3M from Two Year churners. However the most revealing insight comes from combining both numbers: Two Year contracts have 1,900 customers generating $9.04M — approximately $4,758 per customer — while Month-to-Month has 3,600 customers generating only $6.17M — approximately $1,714 per customer. A Two Year customer is worth 2.8x more in lifetime revenue than a Month-to-Month customer. The company has the most customers in its least valuable and highest-risk contract segment simultaneously
7.Does customer count by internet type reflect the true revenue contribution of each segment — or does the revenue picture tell a different story?Customer count alone is misleading for internet type analysis. By count, Fiber Optic leads with 3,000 customers — suggesting it is simply the most popular product. However revenue reveals a more important truth: Fiber Optic generates $12.41M representing 58% of all internet revenue, while DSL generates $4.55M (21%) and Cable only $2.23M (10%). Fiber Optic customers are not just the most numerous — they are individually the most valuable. With 3,000 customers generating $12.41M, each Fiber customer contributes approximately $4,137 in lifetime revenue compared to roughly $2,676 per DSL customer. This means the churn of a single Fiber Optic customer costs the company 55% more than the churn of a DSL customer. Count tells you what customers prefer — revenue tells you what those preferences are actually worth to the business. For Airtel, this means Fiber retention must be treated as a premium priority, not just because it has more customers, but because each one who leaves costs significantly more than any other segment
8.Is the company growing or shrinking — and what does the net customer growth figure mean for long-term revenue sustainability?The company is shrinking. Net Customer Growth of -1K means the company lost approximately 1,000 more customers than it gained this period. With only 454 new customers joining (6.45%) against 1,869 churning (26.54%), the company is replacing less than 1 in 4 of the customers it loses. If this trend continues unchanged, the active customer base — and by extension the $17.69M revenue base — will decline each cycle. More critically, the customers joining spend only $0.02M monthly compared to $0.29M from stayed customers — meaning new customers are entering at entry-level spend and would take years to reach the revenue contribution of churned customers even if fully retained. The company cannot grow its way out of this problem through acquisition alone. Retention must be the primary strategy.
9.When during the customer lifecycle is churn most likely to occur — and what does this mean for retention strategy timing?The customer profile matrix reveals a critical churn window. Churned customers averaged only 17.98 months of tenure before leaving — compared to 41.04 months for stayed customers. This means the average churned customer left before reaching their 18-month mark, while customers who survive beyond 24 months are highly likely to remain long-term. The danger zone is clearly months 1 through 18. New customers who join at $0.02M monthly spend need to be upsold, engaged, and moved onto longer contracts before they reach this window. A structured retention calendar targeting customers at months 6, 12, and 18 with personalised offers — particularly Fiber Optic customers on Month-to-Month contracts aged 45 to 55 with no dependents — would directly address the highest-risk profile identified in the data before churn occurs rather than after.


## Files
| File | Description |
|------|-------------|
| dashboard/telecom_churn_dashboard.pbix | Power BI file |
| images/ | Dashboard screenshots |
| sql/exploratory_queries.sql | SQL queries used |
