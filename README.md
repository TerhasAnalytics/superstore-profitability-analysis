Superstore Profitability Analysis

A Tableau analysis of where a retail business is losing profit, with data-backed recommendations for improving margin.

Tools: Tableau · Tableau Public

Live dashboard: View on Tableau Public

Dashboard overview

The business question

The Superstore earns a 12.47% profit margin. Where is profit being lost, and what changes would raise the margin?

This analysis models a hypothetical goal of raising the margin by 10% (from 12.47% to about 13.7%) over 6 months. The data is a historical sample, so the target is a planning scenario and not a forecast.

The data

Tableau's built-in Superstore sample dataset: orders with sales, profit, discount, product category, customer segment, and region. It is a sample dataset commonly used for practice, not real company data.

Key findings

1. Deep discounts are where the losses come from.

Orders with no discount earn an average profit of $66.90.
Orders discounted above 20% lose $97.20 on average.
Total losses from excessive discounting come to $135,376.

Profit by discount level

2. Furniture sells a lot but earns very little. It has high sales volume but the lowest margin of any category, at only 2.49%.

3. Central region lags. Central's margin is 7.92%, nearly half of West's 14.94%. South has the lowest sales but a healthy 11.93% margin, well above Central's.

Profit by region

4. Home Office is the most profitable segment. It has the fewest orders but the highest margin, at 14.03%.

Recommendations
Cap discounts at 20%. This could recover up to $135,376. That figure is an upper bound, because a cap may also reduce order volume.
Reduce Consumer's reliance on deep discounts. Consumer is the largest segment, and heavily discounted products are where losses concentrate. Dropping the segment would cut revenue sharply, so fixing its discounting is the safer move.
Grow Home Office order volume.
Grow sales in the South region. Its margin is already healthy, so added sales there are more profitable than in Central.
Limitations
Sample data from a past period. The 6-month goal is hypothetical.
The $135,376 recovery is an upper bound. It assumes the same orders would still occur under a 20% discount cap, and customers may buy less if discounts are limited.
Correlation, not proof of cause. Discounts may be concentrated in lower-margin products, so some losses blamed on discounting could reflect product mix. Category and discount should be examined together before acting.
Margin is only one lens. Decisions about segments or product lines would also need customer lifetime value, strategic fit, and costs not captured here.
Repository structure
.
├── README.md
├── images/                     # dashboard screenshots used above
└── superstore_dashboard.twbx   # packaged Tableau workbook
 

Link: https://public.tableau.com/app/profile/terhas.gebreyohannes/viz/Superstore_Profit_Analysis_Capstone2/Story1

Author: Terhas Gebreyohannes · LinkedIn: www.linkedin.com/in/terhas-tekleslassie

Related projects: Medicare Provider Risk Screening · Diabetes Readmission Risk Screening
