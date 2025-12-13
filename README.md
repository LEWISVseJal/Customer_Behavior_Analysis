# 📊 Customer Shopping Behavior Analysis

**End-to-End Data Analytics Project**

---

## 📌 Overview

This project analyzes customer shopping behavior using transactional data to extract meaningful business insights. The analysis follows a complete data analytics lifecycle, including **data cleaning, exploratory data analysis (EDA), SQL-based business analysis, interactive dashboarding in Power BI, and final reporting**. The project demonstrates how data can be transformed into actionable insights to support strategic decision-making.

---

## 🎯 Business Objective

The objective of this project is to understand customer purchasing patterns, identify high-value customer segments, evaluate the impact of discounts and subscriptions, and analyze product performance. These insights can help businesses improve customer retention, optimize marketing strategies, and increase revenue.

---

## 📁 Dataset

* **Total Records:** ~3,900 customer transactions
* **Key Attributes:**

  * Customer demographics (Age, Gender, Location, Subscription Status)
  * Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)
  * Behavioral metrics (Discount Applied, Previous Purchases, Review Rating, Shipping Type)
* **Data Quality:**

  * Minor missing values handled during preprocessing
  * Columns standardized for consistency and readability

---

## 🛠 Tools & Technologies

* **Python:** Pandas, NumPy, Matplotlib, Seaborn
* **SQL:** PostgreSQL / MySQL / SQL Server
* **Business Intelligence:** Power BI
* **Environment:** Jupyter Notebook
* **Database Connectivity:** SQLAlchemy
* **Version Control:** Git & GitHub

---

## 🔄 Project Workflow

### 1. Data Loading & EDA (Python)

* Loaded dataset using Pandas
* Performed exploratory data analysis to understand distributions, trends, and anomalies
* Generated summary statistics and visualizations

### 2. Data Cleaning & Feature Engineering

* Handled missing values in review ratings
* Standardized column names
* Created age groups and purchase frequency features
* Removed redundant or inconsistent columns

### 3. SQL-Based Business Analysis

* Stored cleaned data in a relational SQL database
* Executed SQL queries to answer business questions related to:

  * Revenue distribution by gender
  * Subscriber vs non-subscriber spending behavior
  * High-spending discount users
  * Product performance and ratings
  * Customer segmentation (New, Returning, Loyal)

### 4. Dashboard Development (Power BI)

* Built an interactive dashboard with KPIs and filters
* Visualized customer trends, revenue metrics, and product insights
* Designed for easy interpretation by non-technical stakeholders

### 5. Reporting

* Compiled insights into a structured analytical report
* Included business recommendations based on findings

---

## 🧮 Key SQL Use Cases

* Revenue comparison by customer demographics
* Subscription impact on purchase behavior
* Identification of discount-dependent products
* Customer segmentation using purchase history
* Analysis of repeat buyers and loyalty trends

---

## 📈 Power BI Dashboard

The Power BI dashboard provides a visual overview of:

* Total revenue and average purchase value
* Customer segmentation and subscription impact
* Product category and item-level performance
* Discount usage and shipping preferences
* Revenue contribution by age group

---

## 📊 Key Results & Insights

* Subscribed customers tend to spend more on average
* Loyal customers contribute a significant portion of total revenue
* Certain products rely heavily on discounts to drive sales
* Express shipping users generally have higher purchase values
* Specific age groups contribute most to overall revenue

---

## ⚠️ Challenges & Solutions

* **Missing Data:** Handled using median imputation by product category
* **Redundant Features:** Identified and removed overlapping discount-related columns
* **Query Optimization:** Used aggregations and CTEs for efficient SQL analysis

---

## 🧠 Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* SQL Query Writing and Optimization
* Business Intelligence & Dashboard Design
* Analytical Thinking & Data Storytelling

---

## ▶️ How to Run the Project

### Python Analysis

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy
```

* Open the Jupyter notebook
* Run all cells to perform EDA and data cleaning

### SQL Analysis

* Import the cleaned dataset into PostgreSQL / MySQL / SQL Server
* Execute the SQL queries provided in the `sql` folder

### Power BI Dashboard

* Open the Power BI file
* Refresh the data connection
* Interact with filters and visuals

---

## 📌 Conclusion

This project demonstrates a complete **end-to-end data analytics pipeline**, showcasing practical skills in Python, SQL, and Power BI. It reflects real-world data analysis scenarios and is suitable for data analyst and business analyst roles.
