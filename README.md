# RFM Analysis - Customer Segmentation
This project applies RFM Analysis (Recency, Frequency, Monetary) to segment customers based on their purchasing behavior. The goal is to classify customers into meaningful segments and help businesses optimize their marketing strategies.

## 📌 Project Overview
The RFM Analysis Dashboard provides insights into customer purchasing behavior, helping businesses:

Identify high-value customers.
Detect at-risk customers who need engagement.
Improve marketing strategies for better customer retention.
### 🚀 Key Features
📈 Customer Segmentation –
Classifies customers based on Recency, Frequency, and Monetary (RFM) scores.

🔍 Behavioral Insights –
Understand how often customers buy and how much they spend.

📊 Data Visualization –
Interactive charts and graphs built using Power BI and Python.

🎯 Business Recommendations –
Actionable insights to increase revenue and customer loyalty.

### 🔍 Steps Followed
1️⃣ Data Collection
Sourced the dataset from Kaggle.

2️⃣ Data Cleaning & Preparation
Removed missing values and duplicates.
Standardized data types for consistency.

3️⃣ RFM Score Calculation
Recency (R) – How recently a customer made a purchase.
Frequency (F) – How often a customer makes purchases.
Monetary (M) – How much a customer spends in total.

4️⃣ Customer Segmentation
Categorized customers into 10 segments based on their RFM scores.


## 📊 Customer Segments & Business Strategies

| **Segment Name**       | **Recency (R)**     | **Frequency (F)**    | **Description** |
|----------------------|-----------------|----------------|----------------|
| **Loyal Champions**  | Very High (5)    | Very High (4-5) | Highly engaged and frequent buyers |
| **Loyal Supporters** | High (4-5)       | High (3-4)      | Consistently loyal customers |
| **High Potential**   | High (4-5)       | Moderate (2-3)  | Engaged customers, likely to become loyal |
| **At-Risk Customers**| Low (1-2)        | Moderate (3-4)  | Haven’t purchased recently but have potential |
| **Lost Customers**   | Low (1-2)        | Low (1-2)       | Haven’t engaged in a long time |

## 📢 Marketing Strategies Based on RFM Segments

### 🏆 Loyal Champions (15%)
- 641 customers have made purchases in the last week.
- Generate an average turnover of **6000 currency units**.  

📌 **Strategy:**  
✅ Cross-sell and upsell new products.  
✅ Provide exclusive rewards and offers.  

---

### 💎 Loyal Supporters (818 customers)
- Purchase frequency is **2x higher** than the average customer.
- Monetary value is **50% above** the general customer base.  

📌 **Strategy:**  
✅ Offer personalized promotions.  
✅ Provide early access to new products.  

---

### ⚠️ High Potential Customers (184 customers)
- Last purchase was nearly **two months ago**.
- Their total transaction amounts contribute **significantly** to profitability.  

📌 **Strategy:**  
✅ Offer cashback and discount campaigns.  
✅ Use product recommendations based on similar customer behavior.  

---

### 🔻 At-Risk Customers
- Haven’t interacted recently but had **frequent past purchases**.
- Last purchase was about **four months ago**.  

📌 **Strategy:**  
✅ Provide discounts, rewards, and special incentives.  
✅ Send personalized re-engagement emails.  

---

## 🛠 Technologies Used
- **Python** – `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Jupyter Notebook**
