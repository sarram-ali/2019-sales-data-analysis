# 📊 2019 Retail Sales Data Analysis

## 📌 Project Overview
This project analyzes a full year of retail sales data (January–December 2019) to uncover key business insights related to revenue trends, product performance, customer purchasing patterns, and optimal marketing timing.
The goal is to simulate real-world business intelligence analysis using Python and data visualization tools.

## 📊 Business Questions Answered

#### 1️⃣ What was the best month for sales?

#### 2️⃣ What city sold the most products?

#### 3️⃣ What time should advertisements be displayed?

#### 4️⃣ What products are most often sold together?

#### 5️⃣ What product sold the most?

## 📈 Key Insights

#### 💰 Best Sales Month ----- December (Highest Revenue)
#### 🏙 Top Performing City ----- (San Francisco (CA))
#### ⏰ Peak Purchase Hours ----- Around 11 AM and 7 PM
#### 📦 Frequently Bought Together ----- (AAA Batteries (4-pack))
#### 🔥 Most Sold Product ----- (AAA Batteries (4-pack))

## 💡 Business Recommendations
#### Increase marketing spend during peak sales months.
#### Schedule online advertisements around 11 AM and 7 PM.
#### Bundle frequently purchased products for higher average order value.
#### Focus inventory management on high-demand products.

## 📈 Visualizations
### Best Sales Month ----- December (Highest Revenue)
<img width="1054" height="450" alt="1" src="https://github.com/user-attachments/assets/314e722a-561a-41d8-9b21-e58de2dcbcb4" />
### What product sold the most and why? Releated to its Price
<img width="1200" height="500" alt="5" src="https://github.com/user-attachments/assets/d4e031bc-3166-4864-a957-06259e92f315" />

## 📁 Dataset
Monthly sales data for 2019 including:
- Order ID
- Product
- Quantity Ordered
- Price Each
- Order Date
- Purchase Address
12 CSV files were combined into a single dataset for analysis.

## 🔧 Data Cleaning & Preparation
- Merged 12 monthly datasets
- Removed null rows
- Removed duplicated header rows
- Converted columns to appropriate data types
- Extracted Month, Hour, Year from Order Date
- Created Total Revenue column
- Extracted City & State from Purchase Address

## 🛠 Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly
  
