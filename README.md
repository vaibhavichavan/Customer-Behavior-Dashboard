## 🛍️ Customer-Behavior-Dashboard

This project transforms raw retail transaction data into meaningful insights about customer spending habits, product preferences, and loyalty patterns across demographics and categories.

## 📌 Short Description & Purpose

This project analyzes 3,900 customer purchase records to understand what drives shopping decisions across demographics, product categories, and sales channels. It was built to help a retail company improve customer engagement, optimize marketing strategies, and increase long-term loyalty by answering the core question: *"How can consumer shopping data be leveraged to identify trends and optimize product strategies?"* The pipeline covers the full analytics lifecycle — from raw data cleaning in Python, to structured querying in SQL, to visual storytelling in Power BI.

## 🛠️ Tech Stack

| Layer | Tool / Technology |
|---|---|
| **Data Cleaning & EDA** | Python (Pandas, NumPy) |
| **Database** | PostgreSQL |
| **Data Analysis** | SQL (PostgreSQL queries) |
| **Visualization** | Power BI Desktop |
| **Reporting** | Microsoft Word / PDF |
| **Version Control** | Git & GitHub |

## 📂 Data Source

- **Type:** Retail customer transactional dataset
- **Records:** 3,900 rows × 18 columns
- **Key Fields:**
  
| Field Group | Columns |
|---|---|
| Customer Demographics | Age, Gender, Location, Subscription Status |
| Purchase Details | Item Purchased, Category, Purchase Amount, Season, Size, Color |
| Shopping Behavior | Discount Applied, Previous Purchases, Frequency of Purchases, Review Rating |
| Logistics | Shipping Type, Payment Method |

- **Data Quality:** 37 missing values in `Review Rating` — imputed using median rating per product category
- **Feature Engineering:** Created `age_group` (binned) and `purchase_frequency_days` columns

## ✨ Features & Highlights

- **End-to-End Pipeline** — Raw CSV → Python cleaning → PostgreSQL → Power BI dashboard
- **Customer Segmentation** — Customers classified as New (83), Returning (701), and Loyal (3,116) based on purchase history
- **KPI Cards** — Total customers (3.9K), Average Purchase ($59.76), Average Rating (3.75)
- **Revenue & Sales by Category** — Clothing leads in both revenue and volume across all categories
- **Age Group Analysis** — Young Adults are the top revenue contributors ($62,143)
- **Subscription Insights** — 27% subscribed vs. 73% non-subscribed with comparable average spend (~$59)
- **Discount Impact Analysis** — Identified 839 high-spending discount users and top discount-dependent products (Hat 50%, Sneakers 49.66%)
- **Top-Rated Products** — Gloves (3.86), Sandals (3.84), Boots (3.82) lead in customer ratings
- **Interactive Slicers** — Filter by Subscription Status, Gender, Product Category, and Shipping Type

## ❓ Key Business Questions Answered

1. What is the total revenue breakdown between male and female customers?
2. Which customers used discounts but still spent above the average purchase amount?
3. Which products have the highest average review ratings?
4. Does Express shipping correlate with higher purchase amounts than Standard shipping?
5. Do subscribers spend more on average than non-subscribers?

# 💡 Business Recommendations

- **Boost Subscriptions** — Promote exclusive benefits to convert the 73% non-subscribed base
- **Customer Loyalty Program** — Reward repeat buyers to accelerate movement into the Loyal segment
- **Review Discount Policy** — Balance promotional discounts with profit margin control
- **Product Positioning** — Highlight top-rated items (Gloves, Sandals, Boots) in marketing campaigns
- **Targeted Marketing** — Focus spend on Young Adults and Express-shipping users who show higher purchase intent

## 📸 Dashboard Screenshot

![Customer Behavior Dashboard](https://github.com/vaibhavichavan/Customer-Behavior-Dashboard/blob/main/Dashboard.png)

