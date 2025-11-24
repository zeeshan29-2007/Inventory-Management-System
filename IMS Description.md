📦 Inventory Management System (IMS)

A fully functional Inventory Management System built in Excel that manages customers, vendors, products, purchases, sales, and real-time inventory levels. The system integrates all transactional tables into a central inventory model and visualizes key business insights through a clean, interactive dashboard.

## IMS File
- <a href="https://github.com/zeeshan29-2007/Inventory-Management-System/blob/main/Inventory%20Management%20System.xlsx">IMS File</a>

🚀 Features
✅ Dashboard (Auto-Updated)

Total Customers, Products, Purchase Amount, Sales Amount, Stock Value & Profit/Loss

Top 5 Selling Products (Pie Chart)

Top 5 Customers (Donut Chart)

Stock Level Chart for all products

Low-Stock Auto Notifications (Re-order alerts)

Category slicers for easy navigation

✅ Master Tables

Customer Table – Stores customer details and drives customer analytics

Vendor Table – Manages supplier information for reorders and purchase tracking

Product Table – Contains product codes, cost, purchased units, sold units, and stock

✅ Transaction Modules
Purchase Entry

Records new inventory purchased from vendors

Automatically increases stock count

Updates Purchase Amount and Inventory Value

Sales Entry

Records sales made to customers

Reduces stock in real time

Updates Sales Amount and Profit calculation

🧠 System Architecture
Customers Table ─┐
                  ├── Sales Entry ──┐
Vendors Table ───┘                 │
                                    ├── Inventory Table ─── Dashboard
Products Table ─── Purchase Entry ─┘

📊 Dashboard Preview

Dashboard View
<img width="941" height="428" alt="IMS Dashboard " src="https://github.com/user-attachments/assets/cb45b3aa-7c6c-48ea-bbba-4dfb4f98b8b8" />


Inventory Table View
<img width="883" height="425" alt="IMS Inventory" src="https://github.com/user-attachments/assets/355d0750-0dda-4c51-93e2-8a0564cd75bf" />


📁 Data Tables Included

Table Name	Description

Customers:	Customer records & sales relationship

Vendors:	Vendor information for purchase sourcing

Products:	All product details & costs

Purchase: Entry	New stock purchased from vendors

Sales Entry:	Sales made to customers

Inventory:	Central table combining all data

🛠️ Technologies Used

Microsoft Excel

Data Validation

Lookup Functions (XLOOKUP / VLOOKUP)

Pivot Tables

Pivot Charts

Slicers & Timelines

Conditional Formatting

Dashboard Design

⚙️ How It Works

Add products, customers, and vendors to their tables

Record new purchases & sales through the entry sections

Stock levels update automatically

Inventory table recalculates:

Purchased Units

Sold Units

Available Stock

Stock Amount

Profit/Loss

Dashboard visualizes all insights dynamically

📌 Use Cases

Small businesses tracking daily stock

Retail stores managing incoming & outgoing products

Portfolio/Resume project for Data Analytics

Excel dashboard practice

📥 Installation / Usage

Download the Excel file from this repository

Open the workbook in Microsoft Excel

Enable editing (if prompted)

Explore:

Dashboard

Products

Customers

Vendors

Purchase Entry

Sales Entry

Inventory

⭐ Author

Zeeshan Yaseen
Data Analyst | Excel • Python • Power BI • Data Visualization
