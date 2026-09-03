
# 📊 Supply Chain Management Analytics | Power BI

## 📌 Project Overview

This project is an interactive *Supply Chain Management Dashboard* developed using *Microsoft Power BI, DAX, Power Query, and Data Modeling*.

The dashboard provides insights into:

- Sales Performance
- Store Performance
- Product & Category Analysis
- Inventory & Stock
- Customer Insights

The objective of this project is to transform business data into meaningful insights that support *data-driven decision-making*.

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- DAX
- Power Query
- Data Modeling
- Data Visualization
- GitHub

---

## 🗂️ Data Model

The project consists of the following tables:

### Dimension Tables
- Calendar_Dim
- Customer_Dim
- Product_Dim

### Fact Tables
- Sales_Fact
- Inventory_Fact

The data model is designed to analyze sales, inventory, products, stores, customers, and time-based performance.

---

# 📊 Dashboard Pages

## 1. Sales Overview

This dashboard provides an overview of overall sales and profitability.

### Key Analysis
- Total Sales
- Total Profit
- Total Quantity
- Sales by Category
- Sales by Subcategory
- Sales by Month
- Purchase Quantity by Month

### Business Insight
Sales are distributed across multiple categories, indicating a diversified product portfolio. Monthly sales fluctuations can help identify demand patterns and support better sales and inventory planning.

---

## 2. Store Performance

This dashboard focuses on comparing performance across different stores.

### Key Analysis
- Quantity by Store
- Sales by Store
- Purchase Quantity by Store
- Repeat Customers by Store
- Store Region Analysis

### Business Insight
Store-level analysis helps identify differences in sales performance and customer retention. Stores with lower repeat-customer activity can be further investigated to improve customer engagement.

---

## 3. Product & Category

This dashboard analyzes product, category, and brand performance.

### Key Analysis
- Sales by Category
- Quantity by Category
- ASP by Quantity
- Sales by Brand
- Product Ranking
- Top 10 Products

### Business Insight
Product ranking helps identify high-performing products, while brand and category analysis supports better product assortment, promotion, and inventory allocation decisions.

---

## 4. Inventory & Stock

This dashboard provides visibility into inventory levels and stock availability.

### Key Analysis
- Current Stock by Brand
- Purchase Quantity by Store
- Opening Stock
- Closing Stock
- Stock-Out Flag
- Sales Quantity
- Inventory by Store

### Business Insight
Inventory analysis helps identify stock availability and potential stock-out situations. Combining inventory and sales information can support better replenishment and purchasing decisions.

---

## 5. Customer Insights

This dashboard analyzes customer demographics, geography, loyalty, and retention.

### Key Analysis
- Customers by Region
- Gender Distribution
- Customers by Loyalty Tier
- Repeat Customers by Store
- Customers by City
- Customers by State
- Customers per Store

### Business Insight
Customer analysis helps understand geographic distribution, loyalty behavior, and repeat-customer activity. These insights can support targeted marketing and customer-retention strategies.

---

# 🧮 DAX Measures

The project uses DAX measures for KPI calculations and business analysis.

### Main Measures

- ASP
- AVP
- Current Stock
- MTD Sales
- YTD Sales
- YoY Sales Growth
- Product Rank
- Profit %
- Repeat Customer
- Stock-Out Flag
- Top 10 Product
- Total Customer
- Total Cost
- Total Profit
- Total Quantity
- Total Sales

DAX was also used for ranking, time intelligence, profitability analysis, inventory monitoring, and customer analysis.

---

# 💡 Key Business Insights

- Sales performance can be monitored across categories, subcategories, brands, products, and months.
- Store performance can be compared using sales, quantity, and repeat customers.
- Top-performing products can be identified using product ranking.
- Inventory and stock-out analysis can help improve replenishment decisions.
- Customer distribution can be analyzed by region, city, gender, and loyalty tier.
- Repeat-customer analysis provides insight into customer retention.
- Sales and inventory analysis together can support better supply chain planning.

---

# 🎯 Business Recommendations

1. Monitor monthly sales trends to identify demand fluctuations.
2. Prioritize high-performing products for inventory replenishment.
3. Monitor stock-out situations to reduce potential lost sales.
4. Investigate stores with lower repeat-customer performance.
5. Use regional customer insights for targeted marketing.
6. Analyze product and brand performance when planning inventory.
7. Use sales and inventory trends together for better purchasing decisions.

---

# 📁 Project Structure

```text
Supply-Chain-Analytics/
│
├── README.md
├── Supply_Chain_Analytics.pbix
├── Dashboard_Screenshots/
│   ├── Sales_Overview.png
│   ├── Store_Performance.png
│   ├── Product_Category.png
│   ├── Inventory_Stock.png
│   └── Customer_Insights.png
│
└── DAX/
    └── Measures.md
├── Business_insights
