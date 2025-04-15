
# 🌍 Global Supply Chain Command Center (Power BI Project)

An advanced Power BI dashboard that monitors end-to-end global supply chain KPIs, such as delivery performance, cost per shipment, and inventory dynamics — designed with a fully interactive dark-themed UX inspired by real-time command center interfaces.


### Dataset link -> https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis
---

## 📊 Key Features

- **Interactive KPI Cards**: Sales, Orders, and Transaction counts
- **Time-Sensitive Trends**: Yearly, Quarterly, Monthly revenue and order trends
- **Geographical Analysis**: Sales by country visualized on an interactive map
- **Dynamic Slicers**: Filters by market, region, time, customer segment, and shipment mode
- **Custom Tooltips**: Hover-based deep dives into shipment-level detail
- **Toggle View**: Switch between Year and Quarter using bookmarks and buttons
- **DAX Power**: Includes 5 basic, 3 intermediate, and 8 advanced DAX measures
- **Dark Theme UX**: Consistent professional theme with clean layout and smooth visual transitions

---

## 🧠 DAX Measures Breakdown

### 🔹 Basic
- Total Shipments
- Total Cost
- Total Inventory
- Total Revenue
- Total Orders

### 🔸 Intermediate
- Inventory Turnover
- Average Shipment Cost
- On-Time Delivery Rate

### 🔺 Advanced
- On-Time Delivery % (with USERELATIONSHIP)
- Year-over-Year Inventory Change (SAMEPERIODLASTYEAR)
- Dynamic Cost per Shipment
- Quarterly Performance (DATESQTD)
- Underperformance Alerts
- Dynamic Ranking of Regions (RANKX)
- Cumulative Shipments (ALLSELECTED)
- Forecasted Inventory Levels

---

## 🗃️ Data Model (Snowflake Schema)

**Fact Table**: Orders  
**Dimension Tables**:
- Date (generated with CALENDAR)
- Product
- Customer
- Market
- Shipment

Each dimension table is connected via relationships (some inactive for advanced time intelligence).

---

## 📂 Folder Structure

```
Global-Supply-Chain-Command-Center/
├── data/
│   └── DataCoSupplyChainDataset.csv
├── reports/
│   └── Global_SupplyChain_Dashboard.pbix
├── images/
│   └── dashboard_preview.png
├── README.md
└── LICENSE
```

---

## 🛠 Tools & Technologies

- Microsoft Power BI Desktop
- Power Query (M Language)
- DAX (Data Analysis Expressions)
- Map & Geo-visuals (Bing Maps)
- Bookmarks, Selection Pane, Tooltips

---

## 📸 Preview

![Dashboard Screenshot](images/dashboard_preview.png)

---

## 🧑‍💻 Author

**Built by:** [Your Name]  
**Inspired by:** Real-world global supply chain command centers

---


