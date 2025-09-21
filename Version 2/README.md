# P1_Customer Segmentation & Marketing Campaign Analysis

**Overview**

- This project analyzes customer data from a marketing campaign dataset to uncover spending patterns, segment customers, and provide insights for targeted marketing strategies.
- Version **v2 (Enhanced)** includes improved data cleaning, outlier handling, and updated Power BI visualizations for clearer, more reliable insights.

![Dashboard Visualization](https://github.com/CallmeNavin/P1_Customer-Segmentation-Marketing/blob/main/Version%202/Visualization/Dashboard.png)
_Explore more insights in the full Power BI dashboard_

**Objectives**
- Understand customer demographics and purchasing behavior.
- Segment customers based on **income**, **spending habits**, and **recency**.
- Identify high-value customer groups for targeted campaigns.
- Visualize data for better business decision-making.

**Tech Stack**
- Python: Data cleaning, preprocessing, outlier removal (IQR method).
- Pandas, Matplotlib, Seaborn: Data manipulation & EDA.
- Power BI: Interactive dashboards and visual insights.

**Dataset**
- Original dataset: `marketing_campaign.csv`
- Cleaned dataset after enhancement: `marketing_campaign_clean.csv`
- Source: Kaggle – Marketing Campaign Dataset.

**Data Cleaning & Enhancement**
- Removed null values in key features (`Income`).
- Converted `Dt_Customer` to `TenureDays`.
- Applied IQR method to remove outliers in:
  - Year_Birth
  - Income
  - Spending columns
  - Purchase frequency columns
- Reset indexes after data removal.
- Final cleaned dataset ready for analysis and visualization.

**Power BI Dashboard**
- Customer Segmentation by Income, Spending, and Tenure.
- Top Product Categories by total sales.
- Customer Demographics distribution.
- Purchasing Channels breakdown.

**Key Insights**
- Clearer segmentation after removing extreme outliers.
- Spending patterns now better reflect typical customers rather than being skewed by VIP or data entry errors.
- Improved balance in customer groups → more actionable marketing strategies.

**About Me**

Hi, I'm Navin (Bao Vy) – an aspiring Data Analyst passionate about turning raw data into actionable business insights. I’m eager to contribute to data-driven decision making and help organizations translate analytics into business impact. For more details, please reach out at:

🌐 LinkedIn: https://www.linkedin.com/in/navin826/

📂 Portfolio: https://github.com/CallmeNavin/
