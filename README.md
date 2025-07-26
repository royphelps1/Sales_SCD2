# SCD Type 2 Data Warehouse & Semantic Model – Power BI Project

## 👋 Overview
This Power BI project demonstrates how to build a dimensional data model using flat files, apply Slowly Changing Dimension (SCD) Type 2 logic, and create a business-ready semantic layer with DAX measures, relationships, and clean visualizations.

It simulates a typical star schema used in business reporting environments.

---

## 💾 Datasets
- `Customer.csv` – Original customer dimension
- `Customer_Staging.csv` – Updated customer records to simulate daily changes
- `FactShipment.csv` – Transactional fact table (quantities, sales)
- `DimProduct.csv` – Product dimension
- `DimEmployee.csv` – Employee dimension
- `DateTable` – Created in Power BI using DAX

---

## 🔧 Key Features
- ✅ Implemented **SCD Type 2 logic** in Power Query
- ✅ Maintained historical changes and current views in `DimCustomer`
- ✅ Modeled a clean **star schema**
- ✅ Built a **semantic model layer** using:
  - DAX Measures: `Total Sales`, `Total Quantity`, `Average Order Value`
  - Hierarchies, friendly column names, and cleaned metadata
- ✅ Added **date intelligence** via a custom Date table
- ✅ Created visuals by:
  - Customer
  - Product
  - Employee
  - Month

---

## 📊 Sample KPIs and Visuals
- Total Sales by Customer Name (Bar Chart)
- Total Quantity by Month (Bar Chart)
- Sales Distribution by Employee and Product (Pie Charts)


---

## 📎 Notes
Built using Power BI Desktop with local CSV files as the data source. All logic handled through Power Query and DAX – no external tools or SQL scripts required for this version.

