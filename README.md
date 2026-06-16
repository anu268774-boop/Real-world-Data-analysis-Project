
# 🛒 Retail Sales Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-orange.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Platform](https://img.shields.io/badge/Platform-Kaggle%20Notebook-20BEFF.svg)

---

## 📌 Project Overview

This project performs a complete **Exploratory Data Analysis (EDA)**
on a real-world retail sales dataset (Superstore Sales Dataset).
The goal is to discover meaningful business trends, customer purchasing
patterns, and factors affecting sales performance using statistical
summaries and visualizations.

---

## 📂 Dataset

| Detail | Info |
|--------|------|
| **Name** | Superstore Sales Dataset |
| **Source** | [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) |
| **Records** | 9,994 rows |
| **Features** | 21 columns |
| **Topic** | Retail store sales across USA |

---

## 🎯 Objectives

- Load and understand the dataset
- Examine data structure, dimensions, and data types
- Identify and handle missing values and duplicates
- Generate descriptive statistical summaries
- Perform univariate analysis on individual features
- Perform bivariate and multivariate analysis
- Detect outliers and unusual patterns
- Analyze correlations among numerical features
- Create meaningful visualizations
- Extract actionable business insights

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python 3.8+ | Programming Language |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Kaggle Notebook | Development environment |

---

## 📊 Analysis Performed

### 1. Data Cleaning
- Handled missing values
- Removed duplicate records
- Fixed data types (Order Date, Ship Date)
- Created new features (Order Year, Month, Quarter, Ship Days, Profit Margin)

### 2. Univariate Analysis
- Sales distribution
- Profit distribution
- Order count by Category
- Order count by Region

### 3. Bivariate Analysis
- Sales by Category
- Profit by Region
- Sales vs Profit scatter plot
- Discount vs Profit scatter plot
- Sales by Customer Segment

### 4. Time Series Analysis
- Monthly Sales Trend
- Yearly Sales Trend by Category
- Quarterly Sales Performance

### 5. Multivariate Analysis
- Sales Heatmap (Category vs Region)
- Pair Plot of key numerical features

### 6. Outlier Detection
- Box plots for Sales, Profit, Discount
- IQR method for outlier counting

### 7. Correlation Analysis
- Correlation heatmap of all numerical features

---

## 📈 Key Business Insights

1. **Technology** category leads in both Sales and Profit
2. **High discounts (>20%)** consistently cause negative profit
3. **West region** performs best in total sales
4. **Q4** shows consistent sales peaks every year (festive season)
5. **Consumer segment** drives the highest sales volume
6. **Central region** has the lowest profit margin
7. **Furniture** has high sales but low profit margins
8. Passengers traveling with **small families** show better purchasing patterns

---

## 📁 Project Structure
