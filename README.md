 🛍️ E-Commerce Customer Segmentation — RFM Analysis

Customer segmentation analysis on 500,000+ real retail transactions
using the RFM (Recency, Frequency, Monetary) framework to identify
key revenue segments and provide data-driven marketing recommendations.

 Project Overview
Using the UCI Online Retail dataset covering £8.9M in transactions,
this project calculates RFM scores for 4,338 unique customers, segments
them into 8 behavioral groups, and quantifies the revenue contribution
and churn risk of each segment.

 Key Findings
- 490 Champion customers (11% of base) generate 49.76% of total revenue
- 465 At Risk customers represent £769K in revenue actively drifting away
  with an average 84 days since last purchase — immediate intervention needed
- 88 Can't Lose Them customers are former high-value buyers going cold
  (201 days absent) representing £234K revenue at risk
- 1,504 Hibernating customers are the largest segment by count but
  nearly lost — 186 days average since last purchase

## Business Recommendations

| Segment | Strategic Action Plan |
|---|---|
| 🏆 Champions | VIP rewards, early access, loyalty perks |
| 💎 Loyal Customers | Upsell campaigns, bundle offers |
| ⚠️ At Risk | Win-back emails, limited time discounts |
| 🚨 Can't Lose Them | Personal outreach, premium re-engagement |
| 🌱 Recent Customers | Onboarding emails, first repeat purchase incentive |
| 💤 Hibernating | One final campaign, then reallocate budget |

 Project Structure
- Phase 1 — Data cleaning (135,080 missing CustomerIDs, returns removal)
- Phase 2 — RFM metric calculation per customer
- Phase 3 — Customer segmentation into 8 behavioral groups
- Phase 4 — Visualizations (revenue share, scatter analysis, distributions)

  Tech Stack
- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy

## How to Run
1. Install dependencies:
