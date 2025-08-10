  **1. Business Context & Problem Statement**
This dataset comes from a retail company that sells wine, gold products, meat, fish, and sweets. The company aims to understand customer behavior in order to optimize its marketing campaigns. The business team wants to track total spending by month, analyze product category trends, and identify top customers and best-selling products. The goal of this analysis is to transform raw data into actionable insights that support data-driven marketing and sales strategies.

  **2. Data Cleaning & Preparation**
*Data Import and Initial Exploration*
- Loaded the raw dataset (`marketing_campaign.csv`) into Google Colab and converted `Dt_Customer` to datetime format.  
- Created `Days_Since_Customer` to calculate how long each customer has been with the company.
*Data Cleaning*
- Removed rows with missing `Income` values.  
- Calculated `Total_Spending` as the sum of spending across all product categories.  
- Detected and removed outliers in `Income` using the IQR method.
*Customer Segmentation*
- Created 3-segment groups for `Income`, `Total_Spending`, and `Recency`.  
- Enabled high-level customer segmentation to support marketing insights.
*Data Export for Visualization*
- Saved the cleaned dataset for Power BI visualization.  
- Generated a correlation matrix to explore relationships between income, total spending, and recency.
**Result:** A clean dataset with engineered features, ready for analysis and dashboard creation in Power BI.

**3. Dashboard & Key Insights**
The Power BI dashboard visualizes customer spending behavior and product performance. It helps the business team quickly identify top customers, best-selling products, and overall spending trends.

**Key Insights:**
- Top 3 product categories (Wines, Meat, Gold) contribute ~85% of total product spending.
- The best-selling product (Wines) alone accounts for ~50.4% of total spending.
- Top 5 customers contributes around 52.1% of total revenue, showing high revenue concentration.
- Spending peaked in August 2012 then remained stable in the following months.
- Wines consistently dominates monthly spending (~50%), remaining the core revenue driver.
