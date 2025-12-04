![Grocery Inventory](image/grocery_inventory.png)
This project analyzes a grocery inventory dataset containing 990 products across multiple categories, suppliers, and warehouse locations. The goal is to detect expiry risk, stock-out risk, excess stock, slow movers, and supplier-related issues using a structured data model and a Power BI dashboard. The insights help reduce waste, optimize stock levels, and improve operational efficiency.

The dataset includes product details, category, supplier information, warehouse location, status, stock levels, reorder thresholds, expiration dates, sales volume, turnover rate, and engineered fields such as Days_To_Expire, Near_Expiry, Stock_Gap, Stock_Coverage, and Product_Age. These fields support identifying which products require immediate action and where operational bottlenecks exist.

Key analyses performed:
- Near-expiry products and expired items  
- Stock-out and excess stock risks  
- Category-wise expiry exposure  
- Warehouse expiry distribution  
- Supplier expiry contribution  
- Slow-moving products based on turnover rate  

Core fields used:
Product_Name, Category, Supplier_Name, Warehouse_Location, Status, Date_Received, Last_Order_Date, Expiration_Date, Stock_Quantity, Reorder_Level, Reorder_Quantity, Sales_Volume, Inventory_Turnover_Rate, Days_To_Expire, Near_Expiry, Stock_Gap, Stock_Coverage, Product_Age.

KPIs included:
Total Products, Near Expiry Count, Expired Count, Stock-out Risk Count, Excess Stock Count, Inventory Value, Slow Movers, Supplier Expiry Risk.

Files in this repository:
cleaned_inventory_data.csv  
dashboard.pbix  
grocery_inventory.png  

Tools used:
Python for data preparation and feature engineering  
Power BI for dashboard creation and insights  
