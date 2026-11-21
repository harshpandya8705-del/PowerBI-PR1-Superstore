# Power BI PR1 — Superstore Sales Analysis Dashboard

## Project Overview

This project involves exploring and analyzing the Superstore Sales dataset using Microsoft Power BI. An interactive dashboard has been developed to understand business performance and identify important sales trends.

The report focuses on evaluating sales, profit, product category performance, regional contributions, and customer segments through meaningful visualizations and interactive filters.

The main goal is to convert raw sales records into useful business insights using data preparation, transformation, and visualization techniques.

## Dataset

- **Name:** Sample Superstore Sales Dataset
- **Source:** Kaggle
- **File Format:** CSV
- **Number of Records:** Approximately 9,994

## Tools & Technologies

- Microsoft Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- CSV (Comma-Separated Values)

## Project Structure

```text
PowerBI-PR1-Superstore/
│
├── SampleSuperstore.csv
├── PR1_Harsh.pbix
├── README.md
├── LICENSE
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── documentation/
│
├── documentation/
│   ├── project_overview.md
│   ├── business_requirements.md
│   ├── data_cleaning.md
│   ├── dax_measures.md
│   ├── dashboard_design.md
│   └── insights_and_findings.md
│
├── reports/
│   ├── report_summary.md
│   ├── page1_dashboard.md
│   └── page2_datatable.md
│
├── theme/
├── screenshots/
├── assets/
├── dax/
├── queries/
└── resources/
```

## Implementation Details

### 1. Data Import
- Loaded the Sample Superstore dataset into Power BI Desktop.
- Established a connection with the CSV data source.

### 2. Data Preparation
- Used Power Query Editor to clean and transform the imported data.
- Applied more than eight data preparation and transformation steps.
- Verified column data types and corrected inconsistencies.
- Organized the data for effective reporting and analysis.

### 3. KPI Cards

Developed four key performance indicators to summarize business performance:

- **Total Sales:** Overall revenue generated.
- **Total Profit:** Profit earned from sales.
- **Total Quantity:** Total units sold.
- **Average Discount:** Average discount offered on products.

### 4. Visual Analytics

Implemented the following charts to examine business performance:

- **Sales by Category:** Bar Chart to compare category-wise sales.
- **Profit by Region:** Bar Chart to evaluate regional profitability.

### 5. Slicers & Interactivity

Added interactive slicers to allow users to explore the report dynamically:

- Region
- Category

### 6. Filter Configuration

- Applied page-level filters for report-specific analysis.
- Used visual-level filters to control individual chart data.
- Configured filtering behavior across report elements.

### 7. Report Customization

- Applied a custom Power BI theme.
- Adjusted visual formatting, colors, and layouts.
- Maintained a consistent dashboard design.

### 8. Visual Interaction Settings

- Configured interactions between different report visuals.
- Tested multiple visual interaction combinations.
- Ensured that slicers and charts respond appropriately to user selections.

## Dashboard Screenshots

### Page 1 — Sales Overview

![Sales Dashboard](screenshots/page1_dashboard.png)

### Page 2 — Detailed Data View

![Data Table](screenshots/page2_datatable.png)

## Business Insights

The dashboard enables users to investigate different aspects of Superstore operations, including:

- Overall revenue and profit performance.
- Sales contribution across different product categories.
- Profitability comparison across geographical regions.
- Relationship between product quantity and discount.
- Business performance across different regions and categories.

## How to Run the Project

1. Download or clone this repository to your local system.
2. Find the `PR1_Harsh.pbix` report file.
3. Open the file using Microsoft Power BI Desktop.
4. Navigate through the dashboard pages.
5. Use the Region and Category slicers to filter the data.
6. Explore the charts and visual interactions to understand business performance.

## Project Deliverables

| Deliverable | Location |
|---|---|
| Power BI Dashboard | `PR1_Harsh.pbix` |
| Source Dataset | `SampleSuperstore.csv` |
| Project Documentation | `documentation/` |
| DAX Measures | `dax/` |
| Power Query Files | `queries/` |
| Dashboard Images | `screenshots/` |
| Custom Theme | `theme/` |
| Supporting Resources | `resources/` |

## Author

**Harsh**

Data Analytics | Power BI | Business Intelligence

## Acknowledgement

The Sample Superstore dataset used in this project was obtained from Kaggle. This project is developed for learning and practicing data analytics and business intelligence concepts.
