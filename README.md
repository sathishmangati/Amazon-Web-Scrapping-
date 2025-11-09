# Customer Shopping Behavior Analysis

**End-to-end data analysis** of **3,900 customer transactions** using **Python, PostgreSQL, and Power BI** to uncover **spending patterns, customer segments, and business insights**.

---

## Overview

Analyzed **shopping behavior** across demographics, purchase patterns, discounts, and subscriptions to **drive strategic decisions**.

- **Goal**: Identify high-value customers, optimize discounts, boost subscriptions  
- **Dataset**: 3,900 rows × 18 columns (demographics, items, ratings, shipping, etc.)  
- **Output**: Interactive **Power BI dashboard** + **5 actionable recommendations**

---

## Key Insights

| Business Question | Key Finding |
|-------------------|-----------|
| Revenue by Gender | **Males: €157,890** vs **Females: €75,191** |
| High-Spending Discount Users | 839 customers spent **above average** despite using discount |
| Top 5 Products by Rating | Identified highest-rated items per category |
| Subscribers vs. Non-Subscribers | Subscribers spend **2.1x more on average** |
| Repeat Buyers & Subscriptions | Customers with **>5 purchases** are **3x more likely** to subscribe |

---

## Tech Stack

- **Python**: `pandas` for cleaning, feature engineering  
- **PostgreSQL**: 10+ SQL queries for revenue, segmentation, KPIs  
- **Power BI**: Interactive dashboard with filters (age, category, shipping)  
- **Data Pipeline**: Python → PostgreSQL → Power BI  

---

## Project Workflow

1. **Data Cleaning (Python)**  
   - Imputed **37 missing ratings** using **category median**  
   - Standardized columns to **snake_case**  
   - Engineered: `age_group`, `purchase_frequency_days`  
   - Dropped redundant `promo_code_used`

2. **SQL Analysis (PostgreSQL)**  
   - Revenue by gender, age group  
   - Customer segmentation: New / Returning / Loyal  
   - Top 3 products per category  
   - Discount dependency analysis

3. **Visualization (Power BI)**  
   - Interactive dashboard with slicers  
   - KPIs: Total Revenue, Avg. Spend, Subscription Rate

4. **Recommendations**  
   - Promote **exclusive subscriber benefits**  
   - Reward **repeat buyers** with loyalty tiers  
   - Refine **discount strategy** to protect margins  
   - Target **high-revenue age groups** (35–50)

---

Author
Sathish Mangati
Data Analyst | Python | SQL | Power BI
linkedin.com/in/sathishmangati
github.com/sathishmangati
