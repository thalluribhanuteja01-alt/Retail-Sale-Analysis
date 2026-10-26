# 📊 Retail Sales Analysis Using Python

## Customer Behavior, Product Performance & Sales Trends

## 📌 Project Overview

This project analyzes a retail sales dataset containing 2,000 transactions to understand customer purchasing behavior, product category performance, sales trends, seasonal patterns, quantity preferences, and product pricing.

The analysis was performed using Python, Pandas, Matplotlib, and Seaborn.

The main goal of this project is to explore raw retail sales data, identify meaningful patterns, visualize the results, and convert them into useful business insights.

---

## 🎯 Objectives

The project aims to:

- Understand customer purchasing behavior
- Analyze sales based on customer gender and age
- Identify the best-performing product categories
- Analyze monthly and yearly sales trends
- Study seasonal sales patterns
- Understand purchasing behavior based on quantity
- Compare product prices across categories
- Explore the relationship between age, spending, and product preferences

---

## ❓ Business Questions

1. How does customer age and gender influence purchasing behavior?
2. Are there patterns in sales across different time periods?
3. Which product categories have the highest sales?
4. What is the relationship between age, spending, and product preferences?
5. How do sales change across different seasons?
6. What purchasing patterns can be observed based on the number of items bought per transaction?
7. How are product prices distributed across different categories?

---

## 🗂️ Dataset

The dataset contains retail transaction information.

### Dataset Size

- Rows: 2,000
- Columns: 11

### Main Columns

| Column | Description |
|---|---|
| transactions_id | Unique transaction ID |
| sale_date | Date of transaction |
| sale_time | Time of transaction |
| customer_id | Customer ID |
| gender | Customer gender |
| age | Customer age |
| category | Product category |
| quantity | Number of items purchased |
| price_per_unit | Price per unit |
| cogs | Cost of goods sold |
| total_sale | Total transaction value |

> The original dataset contained the column `quantiy`, which was renamed to `quantity` during data cleaning.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

---

## 🔄 Project Workflow

text
Data Loading
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Data Visualization
     ↓
Business Insights
     ↓
Recommendation

🧹 Data Cleaning
The following steps were performed:
	•	Checked the dataset structure
	•	Checked missing values
	•	Checked duplicate records
	•	Corrected the quantiy column name to quantity
	•	Converted sale_date into datetime format
	•	Prepared the data for further analysis

⚙️ Feature Engineering
New features were created from the transaction date:
	•	Year
	•	Month
	•	Season
The months were grouped into:
	•	Winter
	•	Spring
	•	Summer
	•	Autumn
This helped analyze sales trends over time and across seasons.

📊 Exploratory Data Analysis
1. Gender Distribution
A pie chart was used to understand the distribution of male and female customers.
Observation
The customer base was relatively balanced between male and female customers.

2. Gender vs Total Sales
Total sales were compared between male and female customers to understand differences in revenue contribution.

3. Distribution of Customer Age
A histogram was used to understand the distribution of customer ages and identify the common age groups in the dataset.

4. Age vs Average Total Sale
Average transaction value was calculated for each customer age to understand differences in spending patterns across age groups.

5. Total Sales by Product Category
Sales were grouped by product category to identify the categories generating the highest revenue.
Key Observation
Clothing generated the highest total sales among the analyzed product categories.

6. Monthly Sales Trend
Monthly sales were analyzed to identify changes in sales performance across different months.

7. Year vs Total Sales
Total sales were compared across years to understand yearly changes in sales performance.

8. Sales by Season
Sales were grouped by season to identify differences in sales performance across Winter, Spring, Summer, and Autumn.

9. Quantity vs Average Total Sale
The relationship between the number of items purchased and average transaction value was analyzed.
This helped understand whether larger quantities were associated with higher transaction values.

10. Transactions by Quantity
The number of transactions was analyzed based on the quantity of items purchased.
This helped identify the most common transaction sizes.

11. Product Price Distribution by Category
A box plot was used to compare product price distributions across different categories.
The analysis helps identify differences in typical prices, price ranges, and potential outliers.

12. Age vs Total Sales by Category
Age, total sales, and product category were analyzed together to explore differences in purchasing patterns across age groups.

💡 Key Insights
	•	The customer base was relatively balanced between male and female customers.
	•	Customer spending varied across different age groups.
	•	Clothing generated the highest total sales among the analyzed product categories.
	•	Sales performance varied across different months and years.
	•	Sales differed across different seasons.
	•	Certain transaction quantities were more common than others.
	•	Product prices varied across different categories.
	•	Age and product category analysis showed differences in purchasing patterns.

📈 Business Recommendations
Based on the analysis:
1. Focus on high-performing categories
The business can prioritize inventory and promotional activities for high-performing categories such as Clothing.
2. Use customer demographics
Age and gender patterns can be used to develop more targeted marketing campaigns.
3. Plan for seasonal demand
Seasonal sales patterns can help businesses prepare inventory and promotions in advance.
4. Encourage larger purchases
Bundle offers, quantity discounts, and cross-selling strategies can be considered to encourage customers to purchase more items.
5. Review product pricing
Category-level price distributions can help businesses compare pricing patterns and identify products that require further analysis.

🧠 What I Learned
Through this project, I practiced the basic end-to-end data analysis process:
	•	Data loading
	•	Data cleaning
	•	Missing value analysis
	•	Duplicate checking
	•	Feature engineering
	•	Exploratory data analysis
	•	Data visualization
	•	Business-oriented interpretation
	•	Generating recommendations from data


Project Structure

Retail-Sales-Analysis-Python/
│
├── Retail Sales.csv
├── Retail_Sales_Analysis.ipynb
└── README.md


Future Improvements
The project can be extended by adding:
	•	Power BI dashboard
	•	Customer segmentation
	•	RFM analysis
	•	Profit analysis
	•	Sales forecasting
	•	More detailed category-wise analysis
	•	Interactive visualisations

👩‍💻 About Me
BhanuTeja
B.Tech in ECE Graduate
Skills Practiced
Python Pandas NumPy Matplotlib Seaborn Data Analysis Data Visualization

⭐ Project Purpose
This project was created as part of my learning journey toward becoming a Data Analyst.
The focus was not only on creating visualizations, but also on asking business questions, analyzing the data, identifying patterns, and converting those patterns into meaningful business insights.

