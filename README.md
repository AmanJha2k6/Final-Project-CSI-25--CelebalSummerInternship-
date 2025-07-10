# 📊 Product Performance Dashboard (CSI'25)  — Power BI

This repository contains a **Power BI report** that provides a comprehensive in-depth analysis of product performance across **location**, **date**, **channels**, and **brands**.

---

## 📌 **Objective**

The main goal of this dashboard is to enable:
- Effective tracking of sales metrics.
- Analysis of trends and seasonal patterns.
- Comparison of performance across regions, channels, and brands.
- Data-driven insights to support strategic business decisions.

---

## ✅ **Key Features**

- **Location Analysis:**  
  - Visualize product sales by zone and city using maps and regional charts.
  - Identify high and low performing regions.

- **Date Analysis:**  
  - Trend charts to analyze sales over time.
  - Year-over-year, month-over-month comparisons.
  - Seasonality insights and forecast visuals.

- **Channel Analysis:**  
  - Breakdown of sales across distribution channels.
  - Comparative analysis of channel performance.

- **Brand Analysis:**  
  - Top performing brands by revenue and units.
  - Brand share visuals (treemaps, donut charts).
  - Product-level breakdown within each brand.

- **Interactive Filters & Drilldowns:**  
  - Slicers for dynamic filtering by region, date, channel, and brand.
  - Drill-downs and drill-through pages for deeper exploration.

- **Last Refresh Indicator:**  
  - Card visual shows when the data was last refreshed.

---

## 📊 **Visualizations Used**

- KPI Cards
- Line Charts
- Clustered Column Charts
- Stacked Bar Charts
- Treemaps
- Donut Charts
- Scatter Plots
- Maps (Filled Maps)
- Matrix Tables
- Decomposition Trees

---

## ⚙️ **How to Use**

1. **Open the `.pbix` file** in Power BI Desktop.
2. Download the dataset and connect it if required.
3. Use the slicers to filter data by location, date, channel, and brand.
4. Click on visuals to drill down or drill through to detailed pages.
5. Export insights as needed.

---

## 📑 Table Structure

Below is the structure of the main dataset used in this Power BI project.  
This table supports in-depth product performance analysis across **location**, **date**, **channels**, and **brands**.

| **Column Name**              | **Data Type** | **Description**                                                                 |
|------------------------------|----------------|---------------------------------------------------------------------------------|
| `BILLING DATE`               | Date           | Date when the product was billed/sold. Used for trend and seasonality analysis. |
| `ZONE NAME`                  | Text           | Sales zone or region name (e.g., North, South, East, West).                     |
| `CITY`                       | Text           | City within the zone. Useful for granular regional insights.                    |
| `STOCKIEST NAME`             | Text           | Name of the distributor/stockist handling the product.                          |
| `DISTRIBUTION CHANNEL`       | Text           | Sales channel (e.g., Direct, Retail, Wholesale).                                |
| `SALES OFFICE NAME`          | Text           | Specific sales office or branch.                                                |
| `SALES GROUP NAME`           | Text           | Team or group responsible for sales.                                            |
| `Brand Name`                 | Text           | Product’s brand name. Core dimension for brand analysis.                        |
| `Category Name`              | Text           | Higher-level product category grouping.                                         |
| `MATERIAL DESC`              | Text           | Product description or SKU (stock keeping unit).                                |
| `ACTUAL INVOICED QUANTITY`   | Numeric        | Total units sold. Used to analyze product volume sold.                          |
| `No of Cases sale`           | Numeric        | Number of cases sold (bulk/box quantity).                                       |
| `Unit Rate`                  | Numeric        | Unit selling price of the product.                                              |
| `TOTAL INR VALUE`            | Numeric        | Total invoiced value in INR (or your currency). Key revenue metric.             |
| `Last Refresh` *(calculated)* | DateTime       | Shows the last data refresh timestamp in the report.                            |

---

### 🔑 **How it supports the dashboard**

| **Dimension** | **Key Columns**                                     | **Purpose**                                                   |
|---------------|-----------------------------------------------------|---------------------------------------------------------------|
| **Location**  | `ZONE NAME`, `CITY`                                 | Analyze sales performance by region and city.                 |
| **Date**      | `BILLING DATE`                                      | Analyze trends over time, seasonality, YOY/MOM insights.      |
| **Channel**   | `DISTRIBUTION CHANNEL`, `SALES OFFICE NAME`         | Compare sales performance across channels and sales offices.  |
| **Brand**     | `Brand Name`, `Category Name`, `MATERIAL DESC`      | Deep dive into brand, category, and SKU-level performance.    |
| **Metrics**   | `ACTUAL INVOICED QUANTITY`, `No of Cases sale`, `Unit Rate`, `TOTAL INR VALUE` | Volume, value, pricing insights.                              |
| **Operational** | `STOCKIEST NAME`                                  | Evaluate distributor/partner performance.                     |
| **Governance** | `Last Refresh`                                     | Confirms data freshness for stakeholders.                     |

## 📁 **Repository Structure**

Below is the folder and file structure for this Power BI Product Performance Dashboard project:

### 📁 **Key Files and Folders**

- **`Final Project (Product Performance Analysis.pbix`** — Main Power BI Desktop file containing the data model, visuals, DAX measures, drill-through pages, and design.
- **`Final Project (Product Performance Analysis.pdf`**-Contains the PDF File for those who are unable to access the live link.
- **`Final Project (Product Performance Analysis.pbit`**-Contains the template of power BI.
- **`Product Performance Analysis Jan 22 to July 22_North (Sales_22).xlsx`** — Example dataset with billing, region, channel, brand, and sales metrics for Year 2022.
- **`Product Performance Analysis Jan 23 to July 23_North (Sales_23).xlsx`** — Example dataset with billing, region, channel, brand, and sales metrics for Year 2023.
- **`Images/`** — This file.contains the images of each analysis report pages.
- **`README.md`** — This file. Describes the project, usage, data structure, and publishing steps.

---

✅ **Tip:**  
Keep your folder structure clean — it makes the project easy to clone, open, and understand for anyone who wants to view or extend your dashboard.


## 🔗 Live Dashboard Link:
[Live Link to Dashboard](https://app.powerbi.com/links/DSz8K-GtzH?ctid=34bd8bed-2ac1-41ae-9f08-4e0a3f11706c&pbi_source=linkShare)

## Author
   Aman Jha
