# Global Superstore Sales & Profit Analysis \| Power BI

## Project Overview

This project uses Microsoft Power BI to explore Global Superstore retail
data through business-focused dashboards. The project brief describes a
move from Excel-based analysis to Power BI and asks for reports that
help users understand business performance using data through 2019.

The report contains multiple pages covering sales and profit trends,
geography, products, customers, and additional analytical exercises. It
combines summary visuals with detailed tables and interactive report
elements.

> **Project context:** This is a learning / portfolio project built from
> a provided business-requirements brief and Global Superstore data. It
> is not presented as a deployed solution for a real client.

## Business Questions

The supplied brief asks the dashboard to help answer:

-   What are the overall revenue, profit, order, and customer metrics?
-   How do annual sales change over time?
-   How do monthly sales and profit fluctuate, and are there seasonal
    patterns?
-   Which markets and regions contribute most to sales and profit?
-   How do sales vary by quarter?
-   Can users filter the report by segment and category to get a
    tailored view?

## What the Report Covers

The screenshots provided for this project show pages and visuals related
to:

### 1. Sales Performance

-   Overall sales and profit KPI cards
-   Year-wise sales trends
-   Monthly sales and profit comparisons
-   Quarterly sales analysis
-   Sales contribution by month and year

### 2. Geographic and Regional Analysis

-   Sales and profit by region
-   Sales and profit by country using map visuals
-   Country comparisons and ranking-related tables
-   Regional and country-level breakdowns

### 3. Product and Category Analysis

-   Sales and profit by category and sub-category
-   Product-level profit contribution
-   Most-sold products by region
-   Product quantity analysis for selected sub-categories

### 4. Customer and Segment Analysis

-   Customer counts by segment
-   Average order value by customer
-   Customer-level value metrics
-   Customer growth / churn-related tables
-   Sales and profit comparisons across customer segments

### 5. DAX and Interactive Reporting Concepts

The report screenshots show examples of: - Ranking and top-N analysis -
Cumulative sales - Year-over-year comparisons - Profit percentage and
contribution analysis - Weekday versus weekend comparisons -
Returned-order analysis - Dynamic axis selection using field
parameters - Slicers, bookmarks, drill-related concepts, and
cross-filtering examples

The exact behavior of every interaction has not been independently
tested as part of this repository preparation.

## Tools and Technologies

-   **Microsoft Power BI Desktop** --- report building and visualization
-   **DAX** --- measures and analytical calculations
-   **Microsoft Excel** --- source data
-   **Power Query** --- include this as a tool only if it was used for
    data preparation in the final report

## Repository Structure

``` text
power-bi-global-superstore-sales-analysis/
├── README.md
├── dashboard/
│   └── Global_Superstore_Dashboard.pbix
├── screenshots/
│   ├── sales-overview.png
│   ├── regional-analysis.png
│   ├── product-analysis.png
│   └── advanced-analysis.png
└── data/
    └── README.md
```

The filenames above are suggested names. Replace them with the actual
filenames when adding your files.

## Dashboard Preview

Add 4--6 clear screenshots of the strongest report pages here.
Recommended pages:

1.  Sales overview
2.  Regional / country analysis
3.  Product and category analysis
4.  Customer and segment analysis
5.  Advanced DAX analysis (optional)
6.  Interactive field-parameter page (optional)

Example Markdown for screenshots:

``` markdown
![Sales Overview](screenshots/sales-overview.png)
![Regional Analysis](screenshots/regional-analysis.png)
![Product Analysis](screenshots/product-analysis.png)
![Advanced Analysis](screenshots/advanced-analysis.png)
```

## Key Learning Outcomes

This project provided practice in translating business questions into
report pages, comparing performance across time and geography, exploring
product and customer metrics, and presenting results through Power BI
visuals and interactive controls.

## Data and Usage Note

Before publishing the `.xlsx` source data, confirm that the dataset's
license or course terms permit redistribution. If permission is unclear,
do not upload the original data file. Instead, keep the report file if
it is safe to share and add a short `data/README.md` explaining where
the dataset came from and that the source file is not included.

## How to View the Project

1.  Download the `.pbix` file from the `dashboard/` folder.
2.  Open it with Microsoft Power BI Desktop.
3.  If the report asks for a source file, follow the data instructions
    in `data/README.md` and update the source path if necessary.

## Notes

-   This repository documents a learning and portfolio project.
-   Only include screenshots, files, and data that you are allowed to
    share publicly.
-   Keep personal identifiers, student IDs, and confidential data out of
    public screenshots.
