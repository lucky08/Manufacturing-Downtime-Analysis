# Manufacturing Downtime Analysis (Excel Project)

## 📌 Project Overview

This project analyzes **productivity and downtime data** from a soda bottling production line.  
The raw dataset includes batch-level information such as:

- Operator
- Product
- Batch start & end times
- Downtime duration
- Downtime factors (errors, machine issues, etc.)

Using **Excel Power Query, Power Pivot, DAX, and Macros**, the project transforms raw production data into meaningful performance and efficiency insights.

---

## 🧰 Tools & Skills Used

- **Microsoft Excel**
  - Power Query (data cleaning & transformation)
  - Power Pivot (data modeling)
  - DAX (calculated measures)
  - Pivot Charts & Tables
  - Slicers (interactive filtering)
  - VBA Macros (visual optimization)

---

## 🔄 Data Processing

- Cleaned and standardized raw production data using **Power Query**
- Built relationships between tables in **Power Pivot**
- Created DAX measures for:
  - Error frequency
  - Operator performance
  - Product efficiency
  - Downtime factor analysis

---

## 📊 Key Analyses & Visualizations

### 1️⃣ Operator Struggle with Error (2‑D Column Chart)

- Displays error frequency by operator
- **Macro applied** to:
  - Hide data labels when value = 0
- **Slicer added**:
  - Filter by _Operator Error = Yes / No_

**Insight:** Quickly identifies operators who struggle most with operational errors.

---

### 2️⃣ Operator Performance (2‑D Column Chart)

- Compares operator productivity and performance metrics
- Highlights performance gaps between operators

---

### 3️⃣ Product Efficiency (Conditional Formatting Table)

- Table visualization using conditional formatting
- Color gradients emphasize:
  - High efficiency products
  - Low efficiency products

---

### 4️⃣ Factors for Downtime (2‑D Line Chart)

- Visualizes downtime trends over time
- Categorized by downtime factors (e.g., operator error, machine issues)

**Insight:** Helps identify the most impactful causes of downtime.

---

## 🎯 Business Value

- Identifies operator training opportunities
- Highlights inefficient products
- Pinpoints dominant downtime factors
- Enables data‑driven production optimization

---

## 📁 Repository Structure

```
├── data/
│   └── Raw Manufacturing Downtime Excel Dataset
├── excel/
│   └── Macro-Enabled Manufacturing Downtime Analysis.xlsm
├── README.md
```

---

## 🚀 How to Use

1. Open `Macro-Enabled Manufacturing Downtime Analysis.xlsm`
2. Refresh Power Query connections
3. Use slicers to interact with dashboards
4. Review insights from charts and tables

---

## 📌 Notes

- This project is designed for **Excel‑based analytics portfolios**
- Demonstrates practical use of **Power Query, DAX, and VBA** in manufacturing analytics
