# Revenue and Profit Analytics with SAP Analytics Cloud

**Sales performance dashboard in SAP Analytics Cloud on Global Bike transaction data: revenue, profit and margin KPIs, regional and product-level analysis, and AI-supported insights with Smart Insights and Smart Discovery.**

![SAP Analytics Cloud](https://img.shields.io/badge/SAP-Analytics%20Cloud-0FAAFF?logo=sap&logoColor=white)
![Smart Insights](https://img.shields.io/badge/SAC-Smart%20Insights-0FAAFF?logo=sap&logoColor=white)
![Smart Discovery](https://img.shields.io/badge/SAC-Smart%20Discovery-0FAAFF?logo=sap&logoColor=white)
![KPI Reporting](https://img.shields.io/badge/KPI-Reporting-4479A1)

---

## At a Glance

| Metric | Result |
|---|---|
| Total revenue | **914.0 Million** (group currency) |
| Total profit | **$405.0 Million** |
| Profit margin | **44.3%** |
| Top revenue region | **Bavaria: 98.6M**, followed by Baden-Württemberg (94.8M) and California (86.8M) |
| Top product | **Men's Off Road Bike Fully: 17.55M revenue**, almost twice the next product |
| Most profitable category | **Touring Bikes: 37.7% of profit** |

---

## Dashboard

<img width="100%" alt="Sales Performance Dashboard in SAP Analytics Cloud" src="Sales%20analytics%20Dashboard.png" />

| Visual | Business question |
|---|---|
| **KPI cards** (Revenue, Profit, Profit Margin) | How is the business performing overall? |
| **Revenue by Region** and **Profit by Region** | Which regions drive revenue and profit? |
| **Top 10 Products by Revenue** | Which products matter most? |
| **Sales Quantity by Category** | Which categories sell the most units? |
| **Profit per Product Category** | Which categories actually generate profit? |
| **Profit per Product ID** | Which individual products are the most profitable? |
| **Insight box** | What is the key takeaway for management? |

---

## Business Problem

Global Bike, a bicycle company selling in Germany and the USA, wants to understand its sales performance:

1. **Where does revenue and profit come from?** (regions, categories, products)
2. **Which products drive the business, and how concentrated is revenue?**
3. **Do the categories that sell the most units also bring the most profit?**

---

## Key Insights

1. **Revenue is concentrated in a few products.** *Men's Off Road Bike Fully* brings **17.55M** in revenue, almost **twice** the next product (*Deluxe Touring Bike, silver*: 9.83M).
2. **Germany leads the regional ranking.** **Bavaria (98.6M)** and **Baden-Württemberg (94.8M)** are the top two revenue regions, ahead of California (86.8M). They are also the top two profit regions (46.3M and 44.0M).
3. **Volume is not the same as profit.** **Accessories** sell by far the most units (**186,960**), but profit comes from bikes: **Touring Bikes (37.7%)**, **Road Bikes (29.1%)** and **Off-road Bikes (28.2%)**.
4. **E-Bikes are a small but open segment**, with only **10,887 units** and **5.0% of profit**.
5. **The business is highly profitable overall**, with a **44.3% profit margin**.

### Recommendations

- **Protect the top products** (especially *Men's Off Road Bike Fully*) with stock priority and focused marketing, since revenue depends on a few models.
- **Use accessories as a cross-selling driver** with bikes, since they sell in high volumes.
- **Review the E-Bike strategy**: either invest to grow the segment or keep it as a niche.
- **Use Bavaria and Baden-Württemberg as benchmarks** for weaker regions.

---

## How It Was Built

1. **Data:** Global Bike sales transactions (SAP University Alliances teaching dataset), loaded into SAP Analytics Cloud.
2. **Model:** a KPI model with the measures **Revenue**, **Profit**, **Sales Quantity** and **Profit Margin**, and dimensions for region, product category and product.
3. **Story:** an SAC story with KPI tiles, bar charts, a donut chart and an insight box.
4. **Augmented analytics:** **Smart Insights** to explain top contributors and **Smart Discovery** to find the main profitability drivers.

---

## Tech Stack

| Area | Tools |
|---|---|
| Reporting | SAP Analytics Cloud (stories, KPI tiles, charts) |
| Modelling | SAC data model with calculated measures (Profit Margin) |
| Augmented analytics | SAC Smart Insights, Smart Discovery |
| Data | Global Bike transaction data |

---

## Repository Structure

```
sap-sac-sales-analytics/
├── Sales analytics Dashboard.png   # SAC dashboard
└── README.md
```

---

## Next Steps

- Add **time analysis** (monthly and yearly revenue trends, year-over-year growth)
- Build a **planning version** in SAC for next year's revenue per region
- Use **Smart Predict** to forecast sales per product category
- Model the data in **SAP Datasphere** for a reusable semantic layer

---

## Author

**Mayuresh Parche**
M.Sc. Software Engineering, Hochschule Heilbronn | SAP Certified Data Analyst (SAP Analytics Cloud)

[LinkedIn](https://www.linkedin.com/in/mayureshparche/) | [GitHub](https://github.com/Mayureshp21)
