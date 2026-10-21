# Customer-Segmentation-and-RFM-Analysis and marketing_campaign_ROI analysis
Customer Segmentation and RFM Analysis using SQL Server and Power BI, including customer insights and retention recommendations.

## 1. Project Overview
This project analyzes customer purchasing behavior using RFM (Recency, Frequency, Monetary) analysis. The objective is to identify valuable customer segments and recommend suitable marketing strategies and budget allocation to improve customer retention.

## 2. Business Problem
Which customer segments should a marketing team prioritize for retention campaigns, and how should the marketing budget be allocated across these segments?

## 3. Project Objectives
- Analyze customer purchasing behavior.
- Calculate Recency, Frequency, and Monetary values.
- Assign RFM scores and classify customers into six segments.
- Compare customer counts and sales contribution across segments.
- Build an interactive Power BI dashboard.
- Suggest marketing ideas for each customer group.
- Create a sample campaign ROI analysis using simulated data.

## 4. Tools Used
- SQL Server and SQL Server Management Studio (SSMS)
- Microsoft Power BI

## 5. Project Workflow
1. Validated the sales transaction data.
2. Calculated RFM metrics for each customer.
3. Assigned RFM scores from 1 to 5.
4. Classified customers into Champions, Loyal, Potential, At Risk, Lost, and Others.
5. Analyzed customer counts, sales contribution, and average spending by segment.
6. Created an interactive Power BI dashboard.
7. Created a sample marketing campaign to show how ROI can be calculated

## 6. Key Findings
- Champions and Loyal customers together represent 21.19% of customers and contribute 64.20% of total sales.
- Loyal customers contribute the largest share of sales at 36.66%.
- Potential customers are the largest segment, representing 26.97% of customers.
- At Risk customers represent 14.78% of customers and contribute 11.22% of sales.
- Others represent 20.44% of customers and contribute 2.72% of sales.
- Lost customers represent 16.63% of customers and contribute 1.28% of sales.

## 7. Marketing Recommendations
- Champions: Give special benefits to keep these valuable customers.
- Loyal: Encourage them to buy again.
- Potential: Give suitable offers to encourage more purchases.
- At Risk: Send reminders or offers to encourage them to return.
- Lost: Try low-cost offers to see if these customers return.
- Others: Try low-cost marketing messages and check the results.

## 8. Simulated Campaign ROI
 I created a separate example to show how a company can calculate campaign costs, conversion rates, estimated profit, and ROI.
The campaign results are simulated for learning purposes. They are not results from real marketing campaigns. Actual campaign ROI would need real campaign costs, customer responses, and profit data.

## 9. What I Learned
- How to use SQL to analyze sales data.
- How to calculate RFM scores and group customers.
- How to use Power BI to show data in charts.
- How to find useful business information from data.
- How to suggest marketing plans based on data.

## 10. Project Files

- SQL analysis queries
- Simulated campaign ROI analysis
- Customer insights and recommendations
- Marketing budget allocation plan
- Power BI dashboard screenshot

## 11. RFM Reference Date

31 December 2025.


## Marketing Campaign ROI Analysis (Synthetic Data)

### Project Overview
As an extension of my Customer Segmentation using RFM Analysis project, I developed a Marketing Campaign ROI Analysis to understand how a hypothetical marketing budget could be allocated across different customer segments and how campaign performance could be evaluated.

Since the original sales dataset did not contain marketing campaign costs or conversion data, I created a **synthetic campaign dataset** for demonstration and analysis purposes.

### Tools Used
- **SQL Server (SSMS):** Data preparation, campaign calculations, budget allocation, and ROI analysis.
- **Power BI:** KPI cards, campaign ROI comparison, budget allocation, and conversion rate visualizations.
- **Excel:** Preparation of the synthetic campaign dataset.

### Project Steps

**1. Created Synthetic Campaign Data**

Created hypothetical campaign records for six customer segments:
- Champions
- Loyal
- Potential
- At Risk
- Lost
- Others

The dataset included customers targeted, customers converted, revenue, product cost, and campaign cost.

**2. Calculated Campaign Performance Using SQL**

Used SQL to calculate:
- Conversion Rate
- Net Profit
- Return on Investment (ROI)


**3. Allocated a Hypothetical Marketing Budget**

Proposed a total marketing budget of **₹1,00,000** across the six customer segments.

loyal=25000
potential=25000
champions=15000
atrisk=20000
lost=5000
others =10000
total = 100000
This allocation was a proposed strategy for analysis, not an actual marketing spend.

**4. Created a Marketing Campaign ROI Dashboard in Power BI**

Developed a dashboard to compare campaign performance across customer segments using:
- Total Revenue
- Total Campaign Cost
- Total Net Profit
- Proposed Marketing Budget
- ROI by Customer Segment
- Budget Allocation by Customer Segment
- Conversion Rate by Customer Segment

### Key Findings

- The hypothetical campaigns generated total revenue of ₹2,27,300.
- Total campaign cost was ₹80,000.
- Total net profit was ₹10,920.
- Champions recorded the highest ROI at 140%, followed by Loyal customers at 125%.
- Potential customers generated a positive ROI of approximately 46.67%.
- At Risk and Lost segments recorded negative ROI in the simulated campaign results, indicating that their campaign strategies and costs would need further evaluation.

### Business Recommendations

- Evaluate retention campaigns for Champions and Loyal customers, who showed the strongest simulated ROI.
- Test targeted campaigns for Potential customers to encourage repeat purchases.
- Review campaign messaging, incentives, and costs for At Risk and Lost customers before increasing investment.


### Important Note

**This project uses synthetic campaign data and hypothetical budget allocations for learning and portfolio demonstration.** The campaign revenue, product costs, campaign costs, conversions, net profit, and ROI are simulated values, not actual campaign results. The proposed ₹1,00,000 budget is a planning scenario and is separate from the ₹80,000 simulated campaign cost used in the ROI calculations.

### Skills Demonstrated
SQL querying, data aggregation, calculated business metrics, customer segmentation, marketing budget allocation, ROI analysis, Power BI dashboard development, and business insight generation.
