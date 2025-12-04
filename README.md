# Repository Name
grocery-inventory-expiry-risk-dashboard

# Short Description
A Power BI inventory analytics project focusing on expiry risk, stock health, supplier performance, and operational insights using a 990-product grocery dataset.

---

# Grocery Inventory & Expiry Risk Dashboard

![Grocery Inventory](grocery_inventory.png)

This project analyzes a grocery inventory dataset containing 990 products across multiple categories, suppliers, and warehouse locations. The dashboard highlights expiry risks, stock-out risks, overstock items, slow-moving products, and supplier performance issues using Power BI.

---

## 📊 Project Overview

The dataset includes detailed product-level information:

- Product details (name, category, status)
- Supplier and warehouse information
- Stock levels and reorder thresholds
- Expiration dates and date received
- Sales volume and inventory turnover
- Engineered fields (Days to Expire, Near Expiry, Stock Gap, Stock Coverage, Product Age)

This dashboard helps identify:

- Products nearing expiry  
- Items already expired  
- Overstock and stock-out risk items  
- Supplier-wise expiry patterns  
- Category-wise inventory issues  
- Slow-moving products  

---

## 🛠️ Tools Used
- **Python (Pandas)** → Data cleaning and feature engineering  
- **Power BI** → Dashboard creation and visual analysis  
- **GitHub** → Version control and portfolio documentation  

---

## 📁 Dataset Fields

| Column Name | Description |
|-------------|-------------|
| Product_Name | Name of the item |
| Category | Product category |
| Supplier_Name | Supplier company |
| Warehouse_Location | Warehouse where item is stored |
| Status | Active / Discontinued / Backordered |
| Product_ID | Unique product identifier |
| Supplier_ID | Supplier code |
| Date_Received | Date stock was received |
| Last_Order_Date | Last date item was ordered |
| Expiration_Date | Product expiry date |
| Stock_Quantity | Current units in stock |
| Reorder_Level | Minimum required quantity |
| Reorder_Quantity | Recommended quantity |
| Unit_Price | Selling price |
| Sales_Volume | Total units sold |
| Inventory_Turnover_Rate | Sell-through speed |
| Days_To_Expire | Days left to expire |
| Near_Expiry | Flag for ≤ 30 days |
| Stock_Gap | Difference between current stock and reorder level |
| Stock_Coverage | Estimated number of days stock will last |
| Product_Age | Days since received |

---

## 📈 Key KPIs Calculated

- Total Products  
- Near Expiry Count  
- Expired Products  
- Stock-out Risk Count  
- Excess Stock Count  
- Inventory Value  
- Slow Movers  
- Supplier Risk %  

---

## 🧠 Insights Generated

- Category-wise expiry risk distribution  
- Warehouse-level expiry exposure  
- Supplier expiry patterns  
- High-risk products based on stock coverage  
- Overstocked items blocking inventory value  
- Product movement patterns and slow movers  

---

## 🚀 How to Use This Project

1. Clone the repository  
2. Open the provided CSV file or load your own inventory dataset  
3. Open the Power BI file (`dashboard.pbix`)  
4. Refresh data and explore insights  

---

## 📬 Contact

For any suggestions or collaboration opportunities, feel free to connect!
