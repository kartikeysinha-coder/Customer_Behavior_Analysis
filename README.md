# Customer_Behavior_Analysis
📊 Customer Shopping Behavior Analysis
📌 Overview

This project analyzes customer shopping behavior using transactional data (3,900 records) to uncover insights into spending patterns, product preferences, customer segments, and subscription behavior. The goal is to support data-driven business decisions.

📂 Dataset

- Rows: 3,900

- Columns: 18

- Key Features:

 - Customer demographics (Age, Gender, Location, Subscription Status)

 - Purchase details (Item, Category, Amount, Season, Size, Color)

 - Behavior metrics (Discount, Promo Code, Frequency, Review Rating, Shipping Type)

Missing Values: 37 values in Review Rating

🛠️ Tools & Technologies

- Python (Pandas, NumPy)

- SQL (PostgreSQL / MySQL / SQL Server)

- Power BI

Gamma (for presentation)

🔍 Steps
1. Data Loading & Cleaning (Python)

- Loaded dataset using pandas

- Handled missing values using median imputation

- Standardized column names (snake_case)

- Feature engineering:

  - Age groups

  - Purchase frequency

- Removed redundant columns (e.g., promo_code_used)

2. Database Integration

- Connected Python to PostgreSQL

- Loaded cleaned dataset into database

3. SQL Analysis

Performed business-focused queries:

- Revenue by gender

- High-spending discount users

- Top 5 products by rating

- Shipping type comparison

- Subscribers vs non-subscribers

- Customer segmentation (New, Returning, Loyal)

- Revenue by age group

📊 Dashboard

Built an interactive Power BI dashboard showing:

- Customer count, average purchase, rating

- Revenue by category and age group

- Subscription insights

- Sales distribution

📈 Results & Insights

- Male customers generated higher total revenue

- Discount users can still be high spenders

- Products like Gloves, Sandals, Boots had top ratings (see page 4)

- Express shipping users spend slightly more than standard

- Majority customers are loyal (3000+), indicating strong retention (page 5)

- Young adults contributed highest revenue (page 7)

💡 Business Recommendations

- Improve subscription benefits to increase adoption

- Reward loyal customers with incentives

- Optimize discount strategies for profitability

- Promote top-rated products

- Focus marketing on high-revenue age groups
