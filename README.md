# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior to uncover insights related to demographics, purchasing patterns, subscription usage, discounts, and product performance. The goal is to transform raw transactional data into **actionable business insights** using a complete analytics workflow.

The project demonstrates an **end-to-end data analytics pipeline** using **Python, SQL Server, and Power BI**, making it suitable for a **data analyst portfolio**.

---

## 🎯 Objectives
- Understand customer purchasing behavior across demographics
- Analyze the impact of subscriptions and discounts on revenue
- Identify top-performing products and categories
- Segment customers based on loyalty and purchase history
- Build an executive-ready Power BI dashboard for decision-making

---

## 🧩 Dataset Description
The dataset contains customer-level shopping data, including:
- Customer demographics (age, gender)
- Purchase details (purchase amount, category, item purchased)
- Behavioral data (subscription status, discount usage, purchase frequency)
- Customer history (previous purchases, review ratings)

Source format: **CSV file**

---

## 🛠️ Tools & Technologies
- **Python** (Pandas)
- **SQL Server** 
- **Power BI**
- **SQLAlchemy & pyodbc**
- **Git & GitHub**

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning & Feature Engineering (Python)
- Performed exploratory data analysis (EDA)
- Handled missing values using category-level medians for review ratings
- Standardized column names for SQL and BI compatibility
- Engineered new features:
  - `age_group` (customer segmentation)
  - `purchase_frequency_days` (numeric frequency metric)
- Validated and removed redundant fields

### 2️⃣ Data Storage (SQL Server)
- Loaded the cleaned dataset into SQL Server using SQLAlchemy
- Created a structured fact table optimized for analytics

### 3️⃣ Data Analysis (SQL)
Answered key business questions, including:
- Revenue comparison by gender
- Subscription vs non-subscription spending behavior
- Top-rated products by average review rating
- Discount usage by product
- Customer loyalty segmentation (New, Returning, Loyal)
- Revenue contribution by age group

### 4️⃣ Data Visualization (Power BI)
- Designed an interactive dashboard with:
  - KPI cards (Customers, Revenue, AOV, Ratings)
  - Customer segmentation visuals
  - Category and product performance analysis
  - Discount and subscription insights
- Applied clean design principles and a professional color palette

---

## 📊 Key Insights
- Clothing is the highest-performing category in both revenue and sales volume
- Subscribed customers have higher average spending compared to non-subscribers
- Only a small percentage of customers are subscribed, indicating growth potential
- Young Adult and Adult age groups contribute the most revenue
- Some products rely heavily on discounts, suggesting opportunities for pricing optimization

---

## 💡 Business Recommendations
- Increase subscription adoption through targeted incentives for repeat buyers
- Focus marketing efforts on high-performing categories
- Use age-based segmentation for personalized campaigns
- Optimize discount strategies to balance customer acquisition and profitability

---

## 📈 Power BI Dashboard Preview
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/18a8e50f-5f78-4581-9c32-4ff31f89e003" />


---

## 🚀 How to Run This Project
1. Clone the repository
2. Run the Python notebook to clean and load data into SQL Server
3. Execute SQL queries for analysis
4. Open the Power BI `.pbix` file to explore the dashboard




