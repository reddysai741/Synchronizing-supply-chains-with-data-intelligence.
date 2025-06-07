# Synchronizing-supply-chains-with-data-intelligence.
Build a predictive analytics solution to assess and minimize late delivery risks in a global supply chain network.  Utilize machine learning models (Random Forest, Linear SVC, Gradient Descent), SQL, EDA, and Power BI for data analysis, visualization, and prediction.

## 📁 Dataset

**File:** `DataCoSupplyChainDataset.csv`  
**Records:** 180,519 rows  
**Fields:** 53 columns (sales, product, customer, shipping, profit, category, region, etc.)

## 📌 Project Structure

The project is divided into **three major dashboard segments**:

## 🚚 1. Delivery Risk Management

**Key KPIs (Cards):**
- **Total Shipments**
- **Sum of Sales**
- **Late Delivery Percentage**

**Visuals:**
- 📈 Line Chart: Avg. Days for Shipping (Real vs. Scheduled) by Month  
- 🌍 Map: Order Count by Country  
- 🧮 Bar Chart: Count of Orders by Delivery Status  
- 🥧 Pie Chart: Late, Early, On-Time Breakdown  
- 🔍 Bar Chart: Top 10 Product Categories with Highest Delivery Risk  

**Business Insight:**
Identify bottlenecks in shipping performance, countries with frequent delays, and high-risk categories.

![Screenshot 2025-06-07 201358](https://github.com/user-attachments/assets/19ba3e81-a109-4b92-b655-e7eab976e887)


## 👤 2. Customer Behavior & Satisfaction

**Key KPIs (Cards):**
- **Total Unique Customers**
- **Average Order Value**
- **Customer Profitability**
- **Sum of Sales**

**Visuals:**
- 📈 Line Chart: Sales per Customer Over Time  
- 🛍️ Bar Chart: Top Products by Sales Count  
- 🎯 Bar Chart: Top Products by Revenue  
- 📊 Clustered Column: Product Category vs Region  
- 🗂️ Filters: Year, Department Name

**Business Insight:**
Track loyal customers, most profitable product lines, customer purchase frequency, and geographical demand patterns.



## 📦 3. Product & Shipping Overview

**Key KPIs (Cards):**
- **Sum of Sales**
- **Count of Sales**

**Visuals:**
- 📈 Line Chart: Sales & Benefit per Order by Month  
- 🚚 Bar Chart: Shipping Mode by Delivery Status  
- 🌍 Map: Average Sales by Market  
- 🏷️ Column Chart: Sales by Customer Segment  
- 🥧 Pie Chart: Shipping Mode by Payment Type  

**Business Insight:**
Monitor top-selling items, customer segment contribution, shipping performance, and payment method popularity.

---

## 🎛️ Filters Used

- **Year**
- **Delivery Status**
- **Department Name**
- **Country/Region**
- **Customer Segment**

---

## 🧹 Data Preprocessing Highlights

- Removed sensitive columns (e.g., emails, passwords)
- Converted date fields to datetime format
- Handled null values in product and location columns
- Created new calculated columns (e.g., Delivery Delay, AOV)

---

## 🧠 Insights Gained

- Top revenue-generating regions and products
- Delivery delay patterns by geography and category
- Loyal vs. one-time customers
- Preferred shipping modes and payment types

