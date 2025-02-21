# RFM Analysis - Customer Segmentation
📌 Project Overview
This project applies RFM Analysis (Recency, Frequency, Monetary) to segment customers based on their purchasing behavior. The goal is to classify customers into meaningful segments and help businesses optimize their marketing strategies.

📊 Dataset Information
The dataset is sourced from Kaggle.

🚀 Project Workflow
Data Cleaning

Handled missing values.
Removed duplicate entries.
Calculating RFM Scores

Assigned Recency, Frequency, and Monetary values.
Creating Customer Segments

Categorized customers based on RFM scores.

Business Recommendations

Suggested marketing strategies based on RFM insights.
📈 RFM Segmentation Categories
Segment Name	Recency (R)	Frequency (F)	Description
Loyal Champions	Very High (5)	Very High (4-5)	Highly engaged and frequent buyers
Loyal Supporters	High (4-5)	High (3-4)	Consistently loyal customers
High Potential	High (4-5)	Moderate (2-3)	Engaged customers, likely to become loyal
At-Risk Customers	Low (1-2)	Moderate (3-4)	Haven’t purchased recently but have potential
Lost Customers	Low (1-2)	Low (1-2)	Haven’t engaged in a long time
📉 Key Insights from RFM Analysis
🔹 Loyal Champions (15%)
641 customers made purchases within the last week.
Generate an average turnover of 6000 currency units.
📌 Marketing Strategy:
Introduce cross-sell and upsell strategies.
Promote new products to these customers.
🔹 Loyal Supporters (818 customers)
Average purchase frequency is 8 (2x higher than the general average).
Monetary value is 50% above the general customer base.
📌 Marketing Strategy:
Offer exclusive rewards and personalized promotions.
Provide early access to new products.
🔹 High Potential Customers (184 customers)
Last purchase was nearly two months ago.
Their total transaction amounts contribute significantly to profitability.
📌 Marketing Strategy:
Offer cashback and discount campaigns.
Use product recommendations based on similar customer behavior.
🔹 At-Risk Customers
Haven’t interacted recently but had frequent past purchases.
Last purchase was about four months ago.
📌 Marketing Strategy:
Provide discounts, rewards, and special incentives.
Send personalized re-engagement emails.
🛠 Technologies Used
Python – pandas, numpy, matplotlib, seaborn
Jupyter Notebook
Power BI – for visualization
