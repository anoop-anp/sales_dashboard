# 📊 Sales Dashboard – Power BI Project  

An interactive Sales Analytics Dashboard built using Power BI to monitor business performance and profitability using DAX measures.

---

## 🎯 Project Objective  

This project aims to:

- Track overall business performance  
- Analyze Total Sales, Cost, Profit and Orders  
- Evaluate category and brand contribution  
- Visualize state-wise sales distribution  
- Enable Supervisor-based performance filtering  

---

## 🛠️ Tools & Technologies  

- Power BI  
- Microsoft Excel (Data Source)  
- DAX (Data Analysis Expressions)  
- Data Modeling  

---

## 📂 Project Structure  

sales_dashboard/
│
├── data/
│   └── Complete_Techno_Sales_Data.xlsx
│
├── dashboard/
│   └── sales_powerbi_dashboard.pbix
│
├── images/
│   └── sales_dashboard_preview.png
│
└── README.md
---

## 📊 Dataset Information  

The dataset contains:

- Order Date  
- Order Number  
- Customer Name  
- Product  
- Category  
- Brand  
- Quantity  
- Sales  
- Cost  
- State Code  
- Supervisor  

Additional Tables Used:

- State_list (State & State Code)  
- Supervisor (Supervisor Name & Image URL)  

---

## 📐 Data Modeling  

- Created relationships between:
  - Sales_Data → State_list  
  - Sales_Data → Supervisor  

- Built calculated measures using DAX  

Example DAX Measure:

Total_Profit = SUM(Sales_Data[Sales]) - SUM(Sales_Data[Cost])
Other Measures Created:

- Total_Sales  
- Total_Cost  
- Total_Quantity  
- Total_Orders  

---

## 📈 Key KPIs  

- 99M Total Sales  
- 76M Total Cost  
- 9M Total Profit  
- 13K Total Quantity  
- 5.10K Total Orders  

---

## 📊 Dashboard Features  

- Quantity by Category (Bar Chart)  
- Total Sales by State (Map Visualization)  
- Total Sales by Brand (Pie Chart)  
- Supervisor Interactive Filter  
  - Dashboard updates dynamically based on selected Supervisor  
  - Supervisor images integrated using Image URL column  

---

## 📸 Dashboard Preview  

(Add your screenshot inside the images folder and use:)

![Sales Dashboard](images/sales_dashboard_preview.png)
---

## 💼 Business Insights  

- Compared Sales vs Cost to measure profitability  
- Identified high revenue generating brands  
- Analyzed state-wise sales distribution  
- Evaluated supervisor-level performance  

---

## 👤 Author  

Anoop Singh  
##Email-anooprjy@gmail.com 

