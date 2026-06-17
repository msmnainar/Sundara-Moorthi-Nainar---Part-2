D2C Customer Segmentation – RFM Analysis & Retention Strategy
Project Overview
This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis and clustering to identify high-value, at-risk, and lost customers.

Objective
Build RFM features
Segment customers using KMeans
Interpret segments with real data
Define retention strategies
Data Used
orders.csv
customers.csv
churn_labels.csv
Key Insight from Results
Example observations:

CUST00001 → High spend (2955) but inactive → At Risk
CUST00005 → Good frequency (4) and spend (2550) → At Risk
CUST00003 → Very high recency (171) → Lost
Core Finding
Recency is the strongest driver of churn
High spend alone does NOT ensure retention
Engagement (recent activity) is critical
Segments Identified
High Value
Revenue contributors
Moderate-to-high spend
At Risk
Previously valuable but inactive
Highest priority segment
Lost
Very inactive
Low recovery probability
How to Run
pip install pandas numpy matplotlib seaborn scikit-learn

Open: rfm_segmentation.ipynb

Files
rfm_segmentation.ipynb
segments.csv
retention_strategy.md
manual_review_cases.md
requirements.txt
Conclusion
Customer inactivity is the strongest signal of churn risk.
Retention strategies should focus on re-engaging high-value but inactive users.
