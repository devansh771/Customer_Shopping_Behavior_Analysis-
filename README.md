# Customer Shopping Behavior Analysis

## Overview
This project analyzes customer shopping behavior to uncover insights about spending patterns, product preferences, and customer segments.  
It follows a complete data analytics process — loading and cleaning data in Python, running SQL analysis in MySQL, building a dashboard in Power BI, and creating a final report and presentation.

The goal was to identify trends that help improve marketing strategies, customer retention, and product performance.

## Dataset
- Source: Transactional dataset with 3,900 purchases across multiple product categories  
- Rows: 3,900  
- Columns: 18  
- Key Features:
  - Customer demographics: Age, Gender, Location, Subscription Status
  - Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color
  - Behavioral attributes: Discount Applied, Promo Code Used, Previous Purchases, Review Rating, Shipping Type

## Tools and Technologies Used

Data Preparation → Python (Pandas, NumPy) → Load, clean, and preprocess data  
Data Analysis → MySQL → Run SQL queries for insights  
Visualization → Power BI → Create an interactive dashboard  
Reporting → PowerPoint / Gamma → Present final insights  


## Steps

### 1. Data Loading and Cleaning (Python)
- Imported dataset using pandas.
- Checked data types, missing values, and duplicates.
- Imputed missing values in Review Rating using the median per category.
- Created new features like age_group and purchase_frequency_days.
- Renamed columns to maintain consistency.

### 2. SQL Analysis (MySQL)
Performed structured analysis to answer key business questions:
- Revenue by gender and age group
- Top-rated and most-purchased products
- Discount dependency and impact on sales
- Subscriber vs. non-subscriber spending
- Shipping type comparison
- Customer segmentation (New, Returning, Loyal)

### 3. Dashboard (Power BI)
Built an interactive dashboard to visualize:
- Revenue by customer type
- Purchase frequency
- Top products by category
- Subscription and loyalty behavior
- Revenue by region and age group

### 4. Report and Presentation
Created a detailed PDF report summarizing insights and a presentation using Gamma to present results clearly for stakeholders.

## Results and Insights
- Female customers generated slightly higher revenue.
- Discount users still spent above the average purchase amount.
- Subscribers showed higher purchase frequency and loyalty.
- Express shipping users contributed more revenue.
- Age group-based targeting can improve overall sales performance.

## How to Run
1. Clone the repository:
   ```bash
   https://github.com/devansh771/Customer_Shopping_Behavior_Analysis-
