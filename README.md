# 🌿 Plant Co. Performance Report (Power BI Project)

## 📘 Project Overview
This project presents a **business performance analysis** of a fictional manufacturing and trading company called **Plant Co.**  
The analysis focuses on **Sales, Quantity, and Gross Profit (GP)** for the years **2022–2024**, built with **Microsoft Power BI** and based on raw transactional data in Excel.

The goal of this project is to demonstrate data cleaning, KPI calculation, and visual storytelling using Power BI dashboards.

---

## 🧩 Data Source
**File:** `Plant_DTS.xls`  
**Structure:**
| Column | Description |
|:--------|:-------------|
| `Product_ID` | Unique product identifier |
| `Sales_USD` | Total sales value in USD |
| `Quantity` | Number of units sold |
| `Price_USD` | Unit price in USD |
| `COGS_USD` | Cost of goods sold |
| `Date_Time` | Transaction date |

The dataset covers three years of transactions (2022–2024) across multiple products and countries.

---

## 📊 Power BI Dashboard
The Power BI report (`Performance Report.pbix`) includes three main sections — each focusing on key business metrics.

### 1️⃣ Sales Performance
- **2023:** 13.00M USD *(−512K vs previous year)*  
- **2024:** 3.57M USD *(−135K vs previous year)*  
- **Top insights:**
  - Decrease in sales driven mainly by **China, Sweden, France, and Poland**.
  - Clear **seasonality pattern** between March and July.
  - Consistent sales distribution across product types (Indoor, Landscape, Outdoor).

### 2️⃣ Quantity Performance
- **2023:** 555.6K units *(+17K vs previous year)*  
- **2024:** 148.4K units *(−12K vs previous year)*  
- Monthly trends reveal the highest demand from **March to August**.  
- Product segmentation shows steady performance for “Landscape” items.

### 3️⃣ Gross Profit Performance
- **2023:** 5.15M USD *(−265K vs previous year)*  
- **2024:** 1.40M USD *(−77K vs previous year)*  
- **Gross Margin:** ~39–40% — stable over the entire period.  
- **Top performing countries:** consistent profitability in European markets.  

---

## 📈 Key Insights
- **Stable profitability** despite declining sales volume.  
- **Seasonal fluctuations** in both sales and quantity — strongest in Q2.  
- **Decreasing YoY growth**, especially in Asian markets (China, Thailand).  
- Potential for **portfolio optimization** between product categories.  

---

## 📸 Dashboard Visual

The Power BI dashboard visualizes the main KPIs of Plant Co. — **Sales, Quantity, and Gross Profit** across different countries and product types.  
It includes YTD vs PYTD comparisons, profitability segmentation, and monthly performance trends.

| Overview of Power BI Dashboard |
|:-------------------------------:|
| ![Plant Co Dashboard Preview](https://github.com/adamkowskikuba-cloud/powerbi-plant-co/raw/main/visuals/dashboard_preview.png) |

> *This image illustrates the main layout of the Power BI report, showing YTD vs PYTD performance, top and bottom countries, and GP% segmentation.*  
> *For detailed visuals, check the PDF exports in the [visuals/](./visuals) folder.*

---

## 🧮 Tools & Techniques
- **Power BI** – Data modeling, DAX calculations, KPI visuals.  
- **Microsoft Excel** – Data cleaning and transformation.  
- **Key metrics:** YTD, PYTD, YoY, Gross Profit %, Quantity Trend.  
- **Visualization techniques:** KPI cards, bar & line charts, country-level comparisons.

---

## 🗂️ Folder Structure

📁 powerbi-plant-co
│
├── 📄 README.md
├── 📄 LICENSE
│
├── 📊 data/
│   ├── Plant_DTS.xls
│   └── data_description.txt
│
├── 📊 powerbi/
│   └── Performance Report.pbix
│
├── 📈 visuals/
│   ├── Performance Report 2023 gross profit.pdf
│   ├── Performance Report 2023 quantity.pdf
│   ├── Performance Report 2023 sales.pdf
│   ├── Performance Report 2024 gross profit.pdf
│   ├── Performance Report 2024 quantity.pdf
│   ├── Performance Report 2024 sales.pdf
│   └── dashboard_preview.png

---

## 💬 Conclusions
This project demonstrates:
- Strong understanding of **business KPIs and financial analysis**.  
- Skills in **Power BI dashboard design** and **data-driven storytelling**.  
- Ability to transform **raw data into insights** through visual analytics.  

---

## 👨‍💻 Author
**Created by:** [Your Name]  
**Tools:** Power BI | Excel | DAX | Data Analysis | Visualization  
**Year:** 2025  
