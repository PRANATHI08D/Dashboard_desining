# Dashboard_desining
---
# 📊 Interactive Power BI Dashboard - Financial Analysis

## 🧩 Objective

This project aims to build an **interactive Power BI dashboard** for business stakeholders using the provided Excel dataset (`Financial Sample.xlsx`). The dashboard focuses on key business performance indicators such as **Sales**, **Profit**, and **Growth** to support data-driven decision-making.

---

## 🛠️ Tools Used

- [Power BI Desktop](https://powerbi.microsoft.com/)
- Dataset: `Financial Sample.xlsx` (included in this repo)

---

## 📌 Key Features

### ✅ KPIs Displayed
- 💰 **Total Sales**
- 📈 **Total Profit**
- 💹 **Profit Margin**
- 📊 **Sales Growth (Month/Year over Year)**

### ✅ Interactivity
- **Slicers** for filtering by:
  - Country
  - Segment
  - Product
  - Date
- **Drill-downs** and **tooltips** for deeper insights
- **Filters and dynamic visuals** update based on slicer selections

---

## 📈 Visualizations

| Type            | Description                        |
|------------------|------------------------------------|
| **Cards**        | KPIs like Total Sales and Profit   |
| **Line Chart**   | Sales over Time (Time-Series)      |
| **Bar Chart**    | Sales by Country/Segment           |
| **Pie Chart**    | Profit by Product Category         |
| **Matrix**       | Product-wise breakdown of Sales & Profit |
| **Slicers**      | Interactive filters for user control |

---

## 📅 Time-Series Analysis

The dashboard includes **line charts** showing trends over time. A date hierarchy is created to allow for:
- Yearly view
- Monthly view
- Quarterly comparisons

---

## 🎨 Design & Layout

- **Consistent color theme**
- **Cards** at the top to show totals
- Clean, professional layout using Power BI’s default grid
- **Formatted visuals** with thousands separators and proper number rounding

---

## ⚙️ DAX Measures Used

```DAX
Total Sales = SUM('Financial Sample'[Sales])
Total Profit = SUM('Financial Sample'[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales])

 
