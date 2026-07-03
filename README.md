# Call Center Performance Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-4479A1?style=flat-square&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat-square&logoColor=white)

## Overview

A Power BI dashboard analyzing call center performance — tracking core KPIs, call volume trends by month, and call breakdown by topic. Built to give management a single, consolidated view of performance instead of piecing data together from multiple sources.

## Business Problem

Call center leadership needed visibility into two things: how call volume was trending over time, and which topics/categories were driving the most calls — information that was previously scattered across separate reports.

## Approach

- Structured raw call data into a Power BI model
- Built KPI cards for core call center metrics
- Built a time-series view of calls by month to surface trends
- Built a category breakdown of total calls by topic

## Tech Stack

Power BI · DAX · Power Query

## Key Insights

- Call volume shows a clear month-over-month pattern that management can use for staffing decisions
- Certain topics account for a disproportionate share of total call volume, pointing to where process or self-service improvements would have the most impact

## Screenshots

*Add 1–2 dashboard screenshots here, e.g.:*
`![Dashboard Overview](images/dashboard-overview.png)`

## How to View

This dashboard is a `.pbix` file, which requires Power BI Desktop to open. To make it viewable without installing anything:
- Publish the report to the web via Power BI's "Publish to web" feature and link it here, **or**
- Rely on the screenshots above for a quick view of the dashboard.

## Future Improvements

- Add a drill-through page from the topic breakdown into individual call records
- Add forecasting for expected call volume by month
