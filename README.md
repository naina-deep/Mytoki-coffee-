# Mytoki-coffee-
Interactive Power BI dashboard analyzing MYTOKI coffee sales, revenue, product performance, and purchasing patterns through data-driven insights and visual storytelling.

# &#x20;MYTOKI Coffee Sales Dashboard

**Turning coffee sales data into meaningful business insights with Microsoft Power BI.**

## Project Overview

The **MYTOKI Coffee Sales Dashboard** is a data analytics and business intelligence project designed to explore coffee shop sales performance using Microsoft Power BI.

The project analyzes transaction-level sales data to understand revenue generation, product performance, purchasing patterns, and trends across different times of the day, weekdays, and months.

By transforming raw sales records into meaningful visual insights, this project demonstrates how data analytics can support business understanding and informed decision-making.

## Project Objectives

- Analyze overall coffee sales and revenue performance.
- Identify top-performing coffee products.
- Understand customer purchasing patterns across different times of the day.
- Explore sales distribution across weekdays and months.
- Organize transactional data for effective visualization and analysis.
- Demonstrate practical business intelligence and data storytelling skills.

##  Key Performance Indicators

| Metric                          |          Dataset Result |
| ------------------------------- | ----------------------: |
| Total Transactions              |                   3,547 |
| Total Recorded Sales            |              112,245.58 |
| Average Transaction Value       |                   31.65 |
| Unique Coffee Products          |                       8 |
| Days With Recorded Transactions |                     381 |
| Data Coverage                   | March 2024 – March 2025 |

*Note: The dataset does not explicitly specify the currency, so the recorded sales values are presented without a currency symbol.*

## Key Insights

### &#x20;Product Performance

- **Latte** generated the highest recorded revenue, at 26,875.30.
- **Americano with Milk** recorded the highest transaction count, with 809 transactions.
- Espresso recorded the lowest revenue among the eight products.

### Time-of-Day Analysis

- Afternoon sales totaled 38,130.04.
- Night sales totaled 38,186.34.
- Morning sales totaled 35,929.20.

Sales were distributed relatively evenly across the three recorded time periods.

### Weekly and Monthly Patterns

- Tuesday recorded the highest transaction count among the weekdays, with 572 transactions.
- March 2024 recorded the highest monthly transaction count in the dataset, with 494 transactions.
- Monthly results should be interpreted in the context of the dataset's coverage and completeness.

### Transaction Data

The dataset includes a payment-type field, which can support payment-method analysis. However, all 3,547 records in the supplied dataset are classified as card transactions, so a meaningful comparison between payment methods is not possible with the current data.

## Tools and Technologies

- **Microsoft Power BI** — Dashboard development and data visualization
- **Power Query** — Data preparation and transformation
- **CSV** — Source dataset
- **DAX** — Available for measures and calculations where implemented in the Power BI model

## &#x20;Repository Structure

```text
mytoki-coffee-sales-dashboard/
│
├── COFFEEEE(2).pbix
├── MYTOKI coffee sales(1).csv
├── README.md
└── screenshots/
    └── dashboard-preview.png
```

The `screenshots/` folder and preview image are suggested additions. Add them when you upload an actual screenshot of your dashboard.

## 🚀 Getting Started

### Prerequisites

- Microsoft Power BI Desktop
- Git, if you want to clone the repository
- The included CSV dataset

### Installation and Usage

1. Clone or download this repository.
2. Open `COFFEEEE(2).pbix` using Power BI Desktop.
3. If Power BI requests the source file, update the data source path to the included CSV file.
4. Refresh the dataset if necessary.
5. Explore the dashboard and interact with the available visualizations and filters.

## &#x20;Business Value

This project illustrates how transactional data can be used to:

- Identify products contributing significantly to sales.
- Understand differences in purchasing activity throughout the day.
- Explore temporal patterns in sales performance.
- Support data-informed decisions about product focus, operating periods, and further analysis.

These insights describe historical patterns in the supplied dataset; they do not independently establish the causes of those patterns.

## Future Enhancements

- Add a dedicated KPI summary and executive overview.
- Introduce more detailed time-series analysis.
- Compare product performance across different time periods.
- Incorporate additional payment methods if reliable data becomes available.
- Add a dashboard preview and detailed screenshots.
- Expand the analysis with customer, cost, and profit data if those fields become available.

## About the Project

MYTOKI Coffee Sales Dashboard is a portfolio project demonstrating practical skills in data analysis, business intelligence, dashboard development, and data storytelling.

It showcases the process of turning raw transactional records into an organized analytical resource that helps users explore business performance.

## License

No license has been specified for this repository. Unless a license is added, reuse and redistribution of the project files remain subject to applicable copyright law.

---

**Built with Microsoft Power BI.**
