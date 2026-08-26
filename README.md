# Mineral Production Analysis Dashboard

An interactive Power BI dashboard analyzing India's mineral production and value data, built from raw data sourced and cleaned in Excel.

## 📌 Project Overview

This project explores mineral production across India, broken down by **metallic** and **non-metallic** categories. The workflow covers the full pipeline from raw data to a polished, interactive dashboard:

1. Sourced mineral production data (quantity and value) from official government statistics.
2. Cleaned and structured the raw data in **Excel** — standardizing mineral names, units, and numeric fields.
3. Built an interactive dashboard in **Power BI** to visualize production volumes and values by mineral type.

## 🎯 Objective

To identify which minerals contribute the most to India's mining output — by both **quantity produced** and **economic value** — and present these findings in a clear, filterable dashboard.

## 🗂️ Data Source

Mineral production and value data compiled from official Ministry of Mines / Indian Bureau of Mines statistics.

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data collection, cleaning, and structuring |
| Power BI | Data modeling and dashboard visualization |

## 📊 Dataset

The cleaned dataset (`mineral_production.xlsx`) contains 24 minerals with the following fields:

| Column | Description |
|--------|--------------|
| Mineral Type | Category — Metallic or Non-metallic |
| Mineral | Name of the mineral (e.g., Bauxite, Chromite, Zinc Concentrate) |
| Unit | Unit of measurement (Tonne) |
| Total Quantity | Total quantity produced |
| Total Value (Rs) | Total value in Indian Rupees |

## 📈 Dashboard Features (`mineral_production_dashboard.pbix`)

- **KPI Cards** — Total Minerals Produced (Tonnes) and Total Value (Rs) at a glance
- **Slicer** — Filter the dashboard by mineral / category
- **Column Chart** — Total quantity produced, by mineral
- **Column Chart** — Total value generated, by mineral

## 🔍 Key Insights

- **Bauxite** leads by volume, with over 137 million tonnes produced — the highest of any mineral in the dataset.
- **Zinc Concentrate** generates the highest total value (₹479+ crore/million) despite comparatively low production volume, highlighting its high per-unit worth.
- Several minerals (e.g., Copper Ore, Gold Ore, Lead & Zinc Ore) show a recorded value of 0, likely reflecting unpriced or captive-use production in the source data — worth flagging as a data limitation.

## 📁 Files in This Project

- `mineral_production.xlsx` — Cleaned source dataset
- `mineral_production_dashboard.pbix` — Power BI dashboard file
- `README.md` — Project documentation (this file)

## 🚀 How to Use

1. Open `mineral_production_dashboard.pbix` in Power BI Desktop.
2. Use the slicer to filter by mineral or category.
3. Explore the KPI cards and charts to compare quantity vs. value across minerals.

## 👤 Author

Shaurya — Mining Engineering, IIT (ISM) Dhanbad
