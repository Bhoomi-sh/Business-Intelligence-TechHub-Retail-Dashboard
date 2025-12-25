# TechHub Retail – Business Intelligence Dashboard 

## 📌 Project Overview
This project delivers an **executive-level Business Intelligence dashboard** for *TechHub Retail*, a UK-based online electronics retailer. The dashboard was developed in **Tableau Public** to support senior management with data-driven insights for **strategic planning in 2025**.

The analysis focuses on sales performance, profitability, customer behavior, geographic trends, and forward-looking indicators derived from historical data.

---

## 🗂️ Data Sources
Three datasets were integrated to create a unified analytical view:
- **TechHub_Sales_Data.csv** – Transactional sales data (Jan 2023 – Jun 2024)
- **TechHub_Customers.csv** – Customer demographics and profiles
- **TechHub_Products.csv** – Product, cost, margin, and supplier information

Datasets were connected using Tableau relationships:
- `customer_id` → Sales ↔ Customers  
- `product_id` → Sales ↔ Products  

Date hierarchies (Year → Quarter → Month) were created to enable time-based analysis.

---

## ⚙️ Key Calculated Fields
Several calculated fields were created to enhance business insights:
- **Profit Amount** = Revenue – (Cost Price × Quantity)
- **Profit Margin %**
- **Customer Tenure Days**
- **Customer Lifetime Value (CLV)**
- **Product Age Days**

These metrics enabled deeper analysis of profitability, customer value, and product lifecycle performance.

---

## 📊 Dashboard Design
The dashboard was designed as a **single executive view** combining high-level KPIs with detailed visual analysis.

### Key KPIs:
- Total Revenue
- Average Order Value
- Total Customers
- Customer Acquisition Rate
- Average Profit Margin
- Top Customer Segment

### Visual Components:
- Revenue & profit trends over time
- Geographic performance (region and city-level map)
- Product portfolio analysis by category and margin
- Customer segmentation by tenure and lifetime value
- Supplier performance comparison by revenue

> One unmapped city record was excluded to ensure accurate geographic visualization.

---

## 🎛️ Interactivity & Filters
The dashboard includes interactive features to support exploratory analysis:
- Global date range filter
- Product category multi-select filter
- Customer loyalty tier selector
- Region-to-city drill-down functionality

These elements allow executives to focus on specific strategic questions dynamically.

---

## 📈 Key Insights
- Revenue growth is stable with clear seasonal peaks
- Profitability varies significantly by product category
- High-margin categories (e.g., Tablets, Monitors) outperform others
- Urban regions contribute disproportionately to total revenue
- Gold-tier customers generate significantly higher lifetime value
- A small group of suppliers contributes a large share of revenue

---

## ❓ Business Questions Answered
- Which product categories and suppliers offer the best profit margins?
- How do customer demographics and loyalty tiers impact purchasing behavior?
- What seasonal patterns affect sales and profitability?
- Which acquisition channels deliver the highest lifetime value?
- How does product age relate to sales performance?

---

## 🔮 Predictive & Trend Insights
Due to Tableau Public forecasting limitations, **trendline analysis and month-over-month growth patterns** were used to derive predictive insights.  
Revenue trends indicate **stable growth with moderate seasonal fluctuations**, providing forward-looking guidance for 2025 planning.

---

## 💡 Strategic Recommendations
- Prioritize high-margin products and suppliers
- Focus marketing and retention efforts on high-value customers
- Leverage regional insights for localized promotions and inventory planning
- Use seasonal trends to support proactive decision-making

---

## 🛠️ Tools Used
- Tableau Public
- Data Modeling & Relationships
- Calculated Fields & KPIs
- Interactive Dashboards
