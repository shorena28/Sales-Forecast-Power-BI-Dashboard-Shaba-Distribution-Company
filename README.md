# 📊 Sales, Discount & Margin Analysis Dashboard (Power BI)

## 📌 Overview

This dashboard provides a complete financial view of sales performance, focusing on:

- Revenue vs Discount impact
- Profitability (Margin)
- Cost efficiency
- Brand-level performance
- Forecast vs Historical comparison

👉 Built for data-driven decision-making in distribution & sales environments.

---

# 🎯 Key Objectives

- Understand true revenue after discounts
- Measure profitability by brand
- Track cost efficiency trends
- Compare forecast vs previous year performance
- Identify high-performing and low-performing brands

---

# 📊 Key Metrics (KPIs)

| KPI | Value | Description |
|---|---|---|
| Quantity | 17M | Total units sold |
| Total Sales | 153M | Gross revenue |
| Sales with Discount | 110M | Net revenue |
| Total Discount | 43M | Revenue loss from discounts |
| % Margin | 51% | Overall profitability |

👉 These KPIs provide a quick financial snapshot.

---

# 📈 Dashboard Structure

## 1. 🏷️ Brand Performance Table (Top View)

### Includes

- Plan with Big Amount
- Sales Previous Year
- Total Sales
- 2026 Forecast

### 👉 Insight

- Compare actual vs historical vs forecast
- Detect growth or decline by brand

---

## 2. 🥧 Sales Distribution (Donut Chart)

Shows sales share by brand.

### 👉 Insight

- Identify market leaders
- Understand portfolio balance

---

## 3. 📊 Monthly Performance (Forecast vs Previous Year)

### Visualization

- 🔵 Blue → 2026 Forecast
- 🟡 Yellow → Previous Year

### 👉 Insight

Detect:

- Seasonality
- Growth trends
- Underperformance periods

---

## 4. 💰 Profitability & Cost Efficiency Table

### Includes

- Total Sales Forecast
- Cost Efficiency
- % Margin (Previous Year)
- % Total Cost

### 👉 Insight

Identify:

- High-margin brands
- Cost-heavy brands
- Efficiency leaders

---

## 5. 🥧 Cost Distribution by Brand

Shows cost structure across brands.

### 👉 Insight

- Detect where money is being spent
- Identify cost concentration risks

---

## 6. 📈 Cost Efficiency Trend (Monthly)

### Visualization

- Line → Cost Efficiency (%)
- Bars → Forecast

### 👉 Insight

Monitor:

- Efficiency improvements
- Drops (⚠️ e.g., June dip visible)

---

# 🎛️ Filters (Slicers)

- Brand
- Company
- Region
- Sales Channel
- Year
- Quarter
- Month

👉 Fully interactive dashboard.

---

# ⚙️ Key Calculations

## 💵 Sales with Discount

```DAX
Sales with Discount = Total Sales – Total Discount
