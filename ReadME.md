<div align="center">

# 📊 Samsung Supply Chain & Logistics Dashboard

**A comprehensive Business Intelligence solution built with Microsoft Power BI to analyze end-to-end supply chain operations.**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-FF5722?style=for-the-badge)
![Supply Chain](https://img.shields.io/badge/Supply_Chain-4CAF50?style=for-the-badge)

</div>

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Dashboard Preview](#-dashboard-preview)
- [Key Performance Indicators (KPIs)](#-key-performance-indicators-kpis)
- [Data Model](#-data-model)
- [Business Insights](#-business-insights)
- [Forecasting & Predictive Analytics](#-forecasting--predictive-analytics)
- [Repository Structure](#-repository-structure)
- [Installation & Usage](#-installation--usage)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)
- [License](#-license)

---

## 📖 Project Overview

Modern supply chains generate massive amounts of operational data every day. Without proper analysis, identifying bottlenecks and making informed business decisions becomes a significant challenge.

This project transforms raw supply chain data into an interactive **Business Intelligence (BI)** solution using **Microsoft Power BI**. The dashboard empowers stakeholders to monitor operational performance, identify inefficiencies, optimize inventory, evaluate supplier performance, analyze logistics operations, and track financial metrics. 

By following an end-to-end BI workflow—encompassing data preparation, data modeling, DAX calculations, KPI development, dashboard design, and forecasting—this project delivers actionable business recommendations to optimize the entire supply chain.

---

## ✨ Features

- **Executive Overview**: High-level summary of the entire supply chain operations and financial metrics.
- **Supplier & Procurement Analysis**: Monitors supplier quality scores, lead times, and procurement costs.
- **Production Monitoring**: Tracks manufacturing efficiency, defect rates, and facility performance.
- **Inventory Optimization**: Analyzes inventory turnover, safety stock, and coverage days to prevent overstocking and stockouts.
- **Logistics & Shipment Tracking**: Evaluates carrier performance, on-time delivery rates, and shipment delays.
- **Sales & Profitability Analysis**: Breaks down revenue, profit margins, and product performance.

---

## 🛠️ Tech Stack

- **Business Intelligence**: Microsoft Power BI
- **Data Processing**: Power Query, Microsoft Excel
- **Calculations**: DAX (Data Analysis Expressions)
- **Modeling**: Star Schema, Data Modeling
- **Analytics**: Forecasting, Predictive Analytics

---

## 📈 Dashboard Preview

Here is a detailed look at the interactive dashboards designed for this project:

### 1. Home Dashboard
*Landing page, navigation hub, and project overview.*

![Home Dashboard](Screenshots/Home%20Dashboard.png)

### 2. Executive Overview
*High-level summary of revenue, profit, and overall supply chain health.*

![Executive Overview](Screenshots/Overview%20Dashboard.png)

### 3. Supplier Dashboard
*Procurement metrics, supplier quality scores, and lead time analysis.*

![Supplier Dashboard](Screenshots/Supplier%20Dashboard.png)

### 4. Production Dashboard
*Manufacturing efficiency, defect tracking, and facility performance.*

![Production Dashboard](Screenshots/Production%20Dashboard.png)

### 5. Inventory Dashboard
*Inventory optimization, stock coverage, and turnover analysis.*

![Inventory Dashboard](Screenshots/Inventory%20Performance%20Dashboard.png)

### 6. Shipment Dashboard
*Logistics performance, on-time delivery, and shipping cost analysis.*

![Shipment Dashboard](Screenshots/Shipment%20Dashboard.png)

### 7. Sales Dashboard
*Revenue and profitability evaluation by product and customer channel.*

![Sales Dashboard](Screenshots/Sales%20Dashboard.png)

---

## 📊 Key Performance Indicators (KPIs)

The dashboard tracks and visualizes critical business metrics:

| Category | KPI | Description |
| :--- | :--- | :--- |
| **Financials** | Total Revenue | Overall business revenue generated |
| | Gross Revenue | Revenue calculated before discounts |
| | Total Profit | Net business profitability |
| | Profit Margin | Profitability percentage |
| **Manufacturing**| Production Efficiency| Effectiveness of the manufacturing process |
| | Defect Rate | Product quality and error indicator |
| **Inventory** | Inventory Turnover | Efficiency of inventory movement and sales |
| | Safety Stock | Buffer inventory maintained for emergencies |
| | Stock Coverage Days | Duration current inventory can meet demand |
| **Procurement** | Supplier Quality Score | Metric evaluating overall supplier performance |
| | Average Lead Time | Efficiency of procurement and order fulfillment|
| **Logistics** | Total Shipments | Overall volume of logistics activity |
| | On-Time Delivery Rate| Percentage of deliveries made on schedule |
| | Delayed Shipments | Analysis of shipment delays and bottlenecks |
| **Overall** | Quantity Sold | Total volume of units sold |
| | Perfect Order Rate | Comprehensive supply chain performance metric|

---

## 🗄️ Data Model

The project utilizes a robust **Star Schema** data model to ensure efficient querying and reporting.

![Data Modeling](Screenshots/Data%20Modeling.png)

### Fact Tables
- `Sales`, `Production`, `Inventory`, `Shipments`, `Procurement`

### Dimension Tables
- `Product`, `Supplier`, `Customer`, `Date`, `Region`, `Carrier`

---

## 💡 Business Insights

The analysis identified several critical operational insights:

- **High Manufacturing Standard**: Manufacturing efficiency consistently exceeds **99%**.
- **Reliable Suppliers**: Supplier quality remains consistently high across the board.
- **Top Performers**: Smartphones generate the highest overall revenue and profit margins.
- **Inventory Opportunities**: Optimization opportunities exist primarily for slow-moving products.
- **Logistics Bottlenecks**: Shipment delays are concentrated among specific logistics providers, indicating a need for carrier review.
- **Financial Health**: Profit margins remain robust with revenue demonstrating a steady growth trend.
- **Demand Patterns**: Customer demand strongly correlates with identifiable seasonal patterns.

---

## 🔮 Forecasting & Predictive Analytics

The project leverages advanced analytics to anticipate future business needs:

### Forecasting
- Revenue & Profit Forecasting
- Production & Sales Forecasting
- Inventory & Shipment Forecasting

### Predictive Insights
- **Demand Prediction**: Anticipating seasonal spikes and drops.
- **Supplier Risk Analysis**: Identifying potential procurement failures.
- **Inventory Optimization**: Recommending optimal stock levels dynamically.
- **Shipment Delay Prediction**: Flagging high-risk deliveries.
- **Business Growth Analysis**: Modeling long-term operational scaling.

---

## 📂 Repository Structure

```text
Samsung-Supply-Chain-Dashboard/
│
├── Dashboard/
│   └── Samsung Supply Chain Dashboard.pbix
│
├── Dataset/
│   └── Samsung Supply Chain Dataset.xlsx
│
├── Documentation/
│   └── Project Report.pdf
│
├── Screenshots/
│   ├── Home Dashboard.png
│   ├── Overview Dashboard.png
│   ├── Supplier Dashboard.png
│   ├── Production Dashboard.png
│   ├── Inventory Performance Dashboard.png
│   ├── Shipment Dashboard.png
│   ├── Sales Dashboard.png
│   └── Data Modeling.png
│
├── README.md
└── LICENSE
```

---

## 🚀 Installation & Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/khushalsinghsankhla2808/Samsung-Supply-Chain-Dashboard.git
   ```

2. **Open the Dataset**
   - Review the raw and processed data in the `Dataset/Samsung Supply Chain Dataset.xlsx` file using Microsoft Excel.

3. **Launch the Dashboard**
   - Ensure you have [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.
   - Open `Dashboard/Samsung Supply Chain Dashboard.pbix` to interact with the visualizations.

---

## ⚡ Future Enhancements

- [ ] Integrate AI-based demand forecasting.
- [ ] Implement advanced Machine Learning models for predictive analytics.
- [ ] Establish real-time ERP connectivity.
- [ ] Introduce IoT-enabled supply chain monitoring.
- [ ] Integrate with Microsoft Fabric and Azure Data Lake.
- [ ] Automate Power BI data refresh cycles.
- [ ] Deploy the dashboard to Power BI Service for organizational access.
- [ ] Optimize the dashboard layout for mobile devices.

---

## 👨‍💻 Author

<div align="center">

### Khushal Singh Sankhla

[![GitHub](https://img.shields.io/badge/GitHub-khushalsinghsankhla2808-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khushalsinghsankhla2808)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Khushal%20Singh%20Sankhla-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khushal-singh-sankhla)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:khushalsinghsankhla203@gmail.com)

</div>

---

## 📜 License

This project is developed for educational, analytical, and portfolio purposes. It demonstrates Business Intelligence concepts using Microsoft Power BI and publicly shareable sample data.

---

<div align="center">

**If you found this project useful, please consider giving it a ⭐!**

</div>
