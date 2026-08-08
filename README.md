# Bike Sales Dashboard (Excel Project)

An end-to-end Excel project: cleaning raw bike buyer data, transforming it into an analysis-ready dataset, and building an interactive dashboard with a PivotTable and PivotChart.

## 📂 Files
- `Excel_Project_Dataset.xlsx` — the full workbook, containing:
  - **bike_buyers** — original raw dataset
  - **Worksheet (bike_buyers_transformed)** — cleaned and transformed dataset
  - **Pivot Table** — PivotTable built from the transformed data
  - **Dashboard** — final interactive dashboard

## 🧹 Data Cleaning & Transformation
Performed on the raw `bike_buyers` sheet to produce `bike_buyers_transformed`:
- Removed duplicate records
- Used **Find & Replace** to standardize values across several columns (e.g. expanding abbreviated codes into readable labels — Marital Status, Gender, etc.)
- Added an **Age Bracket** column using nested `IF()` formulas to bucket customers into age groups (e.g. Young Adult, Middle Age, etc.)

## 📊 Analysis
- Built a **PivotTable** summarizing bike purchases across dimensions such as region, income, occupation, and age bracket
- Used the PivotTable as the data source for dashboard visuals

## 📈 Dashboard

![Dashboard Preview](dashboard-preview.png)

The `Dashboard` sheet brings the analysis together into a single interactive view with slicers for **Gender, Marital Status, Region, and Education**, and three linked charts:
- **Average Income by Gender and Bike Purchase** — clustered column chart comparing average income across gender, split by purchase outcome
- **Purchase by Age Bracket** — line chart showing bike purchase counts across Adolescent, Middle Age, and Old age brackets
- **Purchase by Commute Distance** — line chart showing how purchase behavior varies with commute distance (0-1 miles up to more than 10 miles)

All charts and slicers are connected to the same PivotTable, so filtering by any slicer updates the entire dashboard at once.

## 🛠 Tools Used
- Microsoft Excel — Data Cleaning, IF formulas, Find & Replace, PivotTables, PivotCharts, Dashboard Design

## 🔍 Key Skills Demonstrated
- Data cleaning and standardization
- Formula-based feature engineering (Age Bracket)
- Pivot table analysis
- Dashboard design and data storytelling
