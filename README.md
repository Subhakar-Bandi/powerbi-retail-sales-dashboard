# powerbi-retail-sales-dashboard
End-to-end Power BI retail sales dashboard with customer, product, and regional analysis
# 📊 Retail Sales Analysis – Power BI Dashboard

## 📌 Project Overview
This project is an **end-to-end Power BI Retail Sales Dashboard** built to analyze **sales performance, product profitability, customer demographics, and regional trends**.  
The dashboard enables business users to make **data-driven decisions** using interactive KPIs and visuals.

---

## 🗂️ Dataset & Data Model
The project follows a **Star Schema** data model.

### Fact Table
**Transactions**
- Transaction Date  
- CustomerID  
- ProductID  
- StoreID  
- Quantity  
- Discount  
- Payment Method  

### Dimension Tables
**Customers**
- Gender  
- BirthDate  
- City  
- JoinDate  

**Products**
- Category  
- SubCategory  
- Unit Price  
- Cost Price  

**Stores**
- Store Name  
- City  
- Region  

---

## 📄 Dashboard Pages

### 1️⃣ Sales Overview
- KPIs: Total Sales, Total Profit, Total Quantity, Total Transactions  
- Monthly sales trend analysis  
- Sales by Category and Region  
- Interactive slicers (Year, Category, Region)

### 2️⃣ Product Performance
- Top 10 products by sales (Top N analysis)  
- Sales vs Profit by category  
- Profit Margin % analysis  
- Product-level performance insights

### 3️⃣ Customer Analysis
- Customer segmentation by **Age Groups (19–72)**  
- Gender-wise customer distribution  
- Top customers by sales  
- City-wise sales contribution  

### 4️⃣ Region Performance
- Store-wise sales comparison  
- Region-wise sales distribution  
- Location-based performance insights  

---

## 🧮 Key DAX Measures
- Total Sales  
- Total Cost  
- Total Profit  
- Profit Margin %  
- Average Sales per Customer  
- Top N analysis  
- Customer Age & Age Group segmentation  

---

## 🛠️ Tools & Skills Used
- Power BI Desktop  
- DAX (Calculated Columns & Measures)  
- Data Modeling (Star Schema)  
- Data Visualization & Business Analytics  

---

## 🎯 Key Business Insights
- Identified top-performing products and regions  
- Analyzed customer demographics and revenue contribution  
- Evaluated product profitability using margin analysis  
- Tracked monthly and yearly sales trends  

---

## 📁 Repository Contents
- `Retail_Sales_PowerBI_Dashboard.pbix` – Power BI dashboard file  
- `README.md` – Project documentation  

---

## 🚀 How to Use
1. Download the `.pbix` file  
2. Open it using **Power BI Desktop**  
3. Use slicers to explore sales, customers, products, and regions  

---

## 👤 Author
**Subhakar**  
Aspiring Data Analyst  
Skills: Power BI | DAX | SQL | Data Visualization
