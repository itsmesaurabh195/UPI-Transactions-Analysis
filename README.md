# 🚀 UPI Transaction Data Analysis Project

This repository contains the Power BI project for a comprehensive analysis of UPI (Unified Payments Interface) transaction data. The goal is to transform raw transaction records into actionable insights, providing a clear overview of transaction trends, patterns, and financial movements.

---

## 🎯 Project Objective

The primary objective of this project is to:

- Perform robust data transformation and cleaning on raw UPI transaction data using Power Query.
- Conduct thorough data profiling to ensure data quality and integrity.
- Develop an interactive and visually appealing Power BI dashboard that enables users to explore transaction trends, remaining balances, and key performance indicators.
- Provide actionable insights and recommendations based on the analysis to support informed decision-making.

---

## 📊 Dataset

The analysis is based on a dataset containing UPI transaction records. Key fields in the dataset include:

- **Transaction details** (e.g., Transaction ID, Amount, Status, Transaction Time)
- **Participant information** (e.g., Gender, Bank Name Sent, Bank Name Received, Merchant Name)
- **Geographical data** (e.g., City)
- **Device information** (e.g., Device Type)
- **Purpose of transaction**
- **Payment method**
- **Account numbers** (Customer and Merchant)

> The dataset was initially loaded from an Excel file, and further refined through Power Query.

---

## ⚙️ Project Steps

### 🧹 1. Data Transformation

- **Data Loading**: Loaded from Excel using Power BI’s “Transform Data” option.
- **Data Type Conversion**:
  - Converted Customer & Merchant Account Number columns to **Text** format to preserve leading zeros.
- **Column Splitting**:
  - Split Transaction Time into separate **Date** and **Time** columns.
- **Data Type Verification**:
  - Verified all columns (Text, Time, Whole Number, Decimal, Date) to ensure accurate calculations.

---

### 🔍 2. Data Profiling

Used Power Query’s data profiling tools (Column Distribution, Column Profile, Column Quality) to identify and fix:

- Blank values  
- Empty fields  
- Errors  
- Invalid data  

---

### 🎨 3. Dashboard Design & Visualization

- **Slicer Configuration**:
  - Optimized layout and formatting of slicers (e.g., City, Gender, Device Type).
- **Custom Columns**:
  - Created **Age Group** column for demographic segmentation.
- **Visual Elements**:
  - **Line Chart** for monthly transaction trends.
  - **Matrix Visual** for city-wise breakdowns (e.g., Amount, Remaining Balance).
- **Interactivity**:
  - Synced slicers across pages.
  - Used **Conditional Formatting** to highlight key values and trends.

---

### 🔖 4. Bookmark Implementation

- **Transaction Bookmarks**: Allow quick view switching (e.g., overview, monthly view).
- **Remaining Balance Bookmarks**: Provide dedicated views for balance analysis.
- **Bookmarks Navigator**: Added at the top of the dashboard for intuitive navigation.

---

## ✨ Key Insights

- **Monthly Transaction Trends**: Clear seasonal patterns and fluctuations.
- **City-wise Distribution**: Transaction volumes vary across Bangalore, Delhi, Hyderabad, Mumbai.
- **Transaction Purpose Analysis**: Identifies most common transaction types (e.g., Transfer, Payment).
- **Device Usage**: Mobile is the most used device for transactions.
- **Gender Patterns**: Behavioral differences observed via gender slicer.

---

## 💡 Actionable Recommendations

- **Optimize Marketing Campaigns**: Launch during high transaction months.
- **City-Specific Promotions**: Customize based on volume and performance.
- **Improve Device Experience**: Focus on optimizing for mobile users.
- **Fraud Detection**: Use profiling patterns to detect anomalies.
- **Product Development**: Identify financial needs based on transaction purposes.

---

## 🛠️ Tools and Technologies

- **Microsoft Power BI Desktop** – Data transformation, modeling, and dashboard creation  
- **Microsoft Excel** – Source file for transaction data  
- **M Language (Power Query)** – Used for advanced data transformations  

---
