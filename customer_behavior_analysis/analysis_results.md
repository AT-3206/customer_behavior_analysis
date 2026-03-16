# SQL Customer Behavior Analysis -- Results  
  
## Overview  
This document summarizes the key findings from the SQL analysis of the Superstore sales dataset. The analysis focused on customer purchasing behavior, regional sales performance, product profitability, and the impact of discounts on profits.  
  
The objective was to identify trends and insights that could support data-driven business decisions.  
  
---  
  
# Key Findings  
  
## 1. Regional Sales Performance  
  
Revenue varies significantly across geographic regions.  
  
| Region | Revenue |  
|------|------|  
West | $725,457 |  
East | $678,781 |  
Central | $501,239 |  
South | $391,722 |  
  
### Insight  
The **West region generates the highest revenue**, followed closely by the East region. The South region significantly underperforms compared to other regions.  
  
### Business Implication  
Marketing and sales efforts could be expanded in the West and East regions to maximize growth. The South region may require additional market analysis to identify opportunities for improvement.  
  
---  
  
## 2. Customer Segment Contribution  
  
Revenue by customer segment:  
  
| Segment | Revenue |  
|------|------|  
Consumer | $1,161,401 |  
Corporate | $706,146 |  
Home Office | $429,653 |  
  
### Insight  
The **Consumer segment contributes the majority of revenue**, accounting for a large share of total sales.  
  
### Business Implication  
Customer acquisition and retention strategies should prioritize the Consumer segment.  
  
---  
  
## 3. Product Category Profitability  
  
| Category | Revenue | Profit |  
|--------|--------|--------|  
Technology | $836,154 | $145,456 |  
Office Supplies | $719,047 | $122,491 |  
Furniture | $741,999 | $18,451 |  
  
### Insight  
Technology products generate the highest profit margins. Furniture produces strong revenue but significantly lower profit.  
  
### Business Implication  
Promoting higher-margin products such as Technology may improve overall profitability.  
  
---  
  
## 4. Discount Impact on Profitability  
  
Average profit declines significantly as discount levels increase.  
  
| Discount \| Average Profit \|  
|--------|--------|  
0%  | $66.90 |  
10% | $96.06 |  
20% | $24.70 |  
30% | -$45.68 |  
40% | -$111.93 |  
50% | -$310.70 |  
  
### Insight  
Discounts above **30% consistently generate negative profit**, indicating that aggressive discounting erodes margins.  
  
### Business Implication  
Companies should consider implementing discount limits to prevent significant profit losses.  
  
---  
  
## 5. Customer Lifetime Value  
  
Customer lifetime value analysis identifies the most valuable customers based on total spending.  
  
Metrics analyzed include:  
- Total orders per customer  
- Total revenue per customer  
- Average order value  
- Lifetime profit  
  
### Insight  
A small percentage of customers contribute a large share of total revenue.  
  
### Business Implication  
High-value customers should be prioritized for retention strategies and targeted promotions.  
  
---  
  
# Summary  
  
This analysis highlights several key opportunities for improving business performance:  
  
- Limit excessive discounting to protect profit margins.  
- Focus marketing efforts on the Consumer segment.  
- Prioritize high-margin product categories such as Technology.  
- Invest in high-performing regions such as the West.  
- Identify and retain high-value customers.  
  
These insights demonstrate how SQL-based analysis can support strategic decision-making and business optimization.  
  
---
