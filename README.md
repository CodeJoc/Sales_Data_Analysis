# 🛍️ Sales Data Analysis & Dashboard

## 📌 Project Overview
This project analyzes retail sales data (Superstore dataset) to uncover insights into revenue, customer behavior, and product performance.  
The goal is to:
- Clean & preprocess raw sales data
- Summarize key business metrics (KPIs)
- Build an interactive dashboard in Excel/Google Sheets
- Generate insights & recommendations for sales strategy

---

## 📂 Dataset
- **File Used:** `Sample - Superstore.csv` (Kaggle dataset)
- **Rows:** 9,994  
- **Columns:** 21  
- **Key Features:**  
  - `Order Date`, `Sales`, `Profit`, `Quantity`  
  - `Region`, `Category`, `Segment`, `Customer ID`  
  - `Product Name`, `Order ID`, etc.

---

## ⚙️ Steps Performed

### 1. Data Cleaning
- Removed duplicates
- Handled missing values
- Converted date columns (`Order Date`, `Ship Date`) into datetime
- Verified numeric columns (`Sales`, `Profit`, `Quantity`)

### 2. KPI Calculation
- **Total Revenue**
- **Total Profit**
- **Total Orders**
- **Average Order Value (AOV)**
- **Monthly Sales Trend**

### 3. Sales Analysis
- Revenue by **Product Category**
- Revenue by **Region**
- **Top 5 Products** by sales
- **Customer Segmentation** using RFM (Recency, Frequency, Monetary)

### 4. Dashboard Preparation
- Exported processed data into `sales_dashboard.xlsx` with multiple sheets:
  - `cleaned_data`
  - `KPIs`
  - `Monthly Sales`
  - `Category Sales`
  - `Region Sales`
  - `Top Products`
  - `Customer Segments`

### 5. Dashboard Creation (Excel/Google Sheets)
- Added pivot charts & slicers:
  - **Monthly Sales Trend** → Line chart
  - **Sales by Category/Region** → Bar/Column charts
  - **Top 5 Products** → Column chart
  - **KPIs** → Cards for quick overview
- Built a **Dashboard sheet** with interactive filters

---

## 🚀 How to Run in Google Colab

1. Upload the dataset (`Sample - Superstore.csv`) to Colab.
2. Run the provided **Colab notebook**:
   ```python
   !pip install xlsxwriter openpyxl
