
# Chocolate-sales-analysis
Interactive Chocolate Sales Analysis Dashboard built using Power BI. Features salesperson ranking from highest to lowest sales, top-selling products, total boxes sold, monthly sales trend analysis, and an interactive date-range timeline slicer to explore sales performance.

# Chocolate Sales Analysis Dashboard

An interactive **Power BI dashboard** designed to explore chocolate
sales performance across products, countries, salespeople, and time. The
project uses a sample sales dataset containing 4,998 records and
presents key business metrics in a single view to support data-driven
analysis.

## Dashboard Preview

![Chocolate Sales Analysis]

> To display the preview on GitHub, add the dashboard screenshot to your
> repository at `images/chocolate-sales-dashboard.png`. You can change
> the image path above to match your folder structure.

## Project Overview

The dashboard provides an overview of sales performance and allows users
to explore results over a selected date range. It brings together
high-level KPIs and detailed breakdowns to help identify sales trends,
leading products, high-performing markets, and salesperson performance.

## Dataset

The analysis is based on `sample-chocolate-sales-data-1.xlsx`.

  Dataset detail                                   Value
  ---------------- -------------------------------------
  Records                                          4,998
  Columns                                              7
  Salespeople                                         25
  Products                                            22
  Countries                                            6
  Date coverage      2 January 2023 -- 30 September 2024

### Data fields

  -----------------------------------------------------------------------
  Column                              Description
  ----------------------------------- -----------------------------------
  `Sales Person`                      Name of the salesperson associated
                                      with the record

  `Product`                           Chocolate product sold

  `Country`                           Country associated with the sale

  `Date`                              Date of the sales record

  `Amount`                            Sales amount recorded for the
                                      transaction

  `Boxes`                             Number of boxes recorded for the
                                      transaction

  `Order Status`                      Current order status (Delivered,
                                      Shipped, Cancelled, or Placed)
  -----------------------------------------------------------------------

## Dashboard Features

-   **KPI cards:** High-level view of total revenue and total boxes
    sold.
-   **Monthly sales trend:** Tracks how sales amount changes month by
    month.
-   **Product performance:** Compares sales amount across chocolate
    products.
-   **Country-wise sales:** Shows the contribution of each country to
    overall sales.
-   **Salesperson performance:** Compares sales contribution across
    individual salespeople.
-   **Date-range slicer:** Filters the dashboard to a selected reporting
    period.

## Key Observations from the Dataset

The following figures are calculated from the complete Excel dataset,
before applying dashboard filters:

-   **Total sales amount:** 27.99 million (dataset units).
-   **Total boxes sold:** 1.99 million.
-   **Top country by sales amount:** UK, at approximately 7.66 million.
-   **Top product by sales amount:** Orange Choco, at approximately 1.86
    million.
-   **Top salesperson by sales amount:** Brien Boise, at approximately
    2.17 million.

Dashboard KPI values may differ from these full-dataset totals when a
date range or other report filter is applied.

## Tools Used

-   **Microsoft Power BI** -- dashboard development and data
    visualization.
-   **Microsoft Excel** -- source dataset and data review.

## Business Questions Explored

1.  How does sales revenue change over time?
2.  Which chocolate products generate the highest sales amount?
3.  Which countries contribute the most to overall sales?
4.  Which salespeople contribute the most to sales?
5.  How do sales results change across different date ranges?
6.  How many boxes are sold during the selected reporting period?

## Repository Structure

``` text
Chocolate-Sales-Analysis/
│
├── data/
│   └── sample-chocolate-sales-data-1.xlsx
│
├── images/
│   └── chocolate-sales-dashboard.png
│
├── Chocolate-Sales-Analysis.pbix
│
└── README.md
```

*The structure above is a suggested layout. Update the file and folder
names to match the contents of your repository.*

## How to Explore the Project

1.  Clone or download this repository.
2.  Open `Chocolate-Sales-Analysis.pbix` using Power BI Desktop.
3.  If Power BI requests the source file, update the data source path to
    the Excel file in the `data` folder.
4.  Refresh the data if required.
5.  Use the date-range slicer and dashboard visuals to explore sales
    performance.

## Project Goal

The goal of this project is to turn raw sales records into an
interactive business dashboard that makes it easier to monitor
performance, compare sales across dimensions, and identify useful
patterns in the data.

------------------------------------------------------------------------

**Created as a data analytics and visualization project using Microsoft
Power BI.**

