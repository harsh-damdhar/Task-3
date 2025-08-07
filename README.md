# Task-3
completing my task-3 create a dashboard and summarize it into ppt.
# 📊 Sales & Financial Dashboard (Power BI)

## 📘 Project Overview

This interactive Power BI dashboard provides business stakeholders with a comprehensive view of key financial metrics, including **Sales**, **Profit**, and **Growth trends**. Built using a sample Kaggle sales dataset, the dashboard allows users to filter and analyze performance by **Region**, **Segment**, **Category**, and **Time**.

---

## 🚀 Features

- 📈 KPI Cards: Total Sales, Total Profit, YoY Growth %
- 🗓 Time Series Analysis: Sales and Profit by Month
- 🗺 Breakdowns: Sales and Profit by Region and Category
- 🎛 Slicers: Interactive filters for Date, Region, Segment, Category
- 🧭 Navigation Pane: Switch between different report views
- 🎨 Consistent Color Theme: Professional blue/white palette for clarity

---

## 📊 KPIs Used

| KPI              | Formula / Measure (DAX)                          |
|------------------|--------------------------------------------------|
| Total Sales      | `SUM(Sales[Sales])`                              |
| Total Profit     | `SUM(Sales[Profit])`                             |
| Profit Margin %  | `DIVIDE(SUM(Sales[Profit]), SUM(Sales[Sales]))` |
| YoY Growth       | See `YoY Sales Growth` measure below             |

---

## 🧠 Power BI Dashboard
