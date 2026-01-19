# EV Charging Station Operations & Revenue Analytics

## 📌 Project Overview
This project is an end-to-end **data analytics portfolio project** focused on analyzing the **operational performance and revenue efficiency of EV charging stations** across major Indian cities.

The objective is to help business and operations teams understand:
- How charging stations are utilized
- Which locations and charger types generate the most revenue
- Where operational inefficiencies exist
- How performance varies across cities and time

---

## 🎯 Business Objectives
- Analyze **revenue performance** across cities and charging stations
- Measure **station utilization** using session volume
- Compare **Fast vs Standard chargers** for revenue efficiency
- Identify **high-performing and underperforming locations**
- Present **executive-ready insights** using dashboards and storytelling

---

## 🧱 Dataset Description

### 1️⃣ charging_sessions_raw.csv (Fact Table)
Each row represents a single EV charging session.

**Key Columns:**
- `session_id` – Unique charging session
- `session_date` – Date of charging
- `city` – City where charging occurred
- `station_id` – Charging station identifier
- `operator` – Charging network operator
- `charger_type` – Fast / Standard
- `energy_kwh` – Energy consumed (kWh)
- `duration_min` – Charging duration (minutes)
- `revenue` – Revenue generated per session

---

### 2️⃣ stations_dimension.csv
Provides station-level metadata.
- `station_id`
- `city`
- `operator`

---

### 3️⃣ date_dimension.csv
Calendar table used for time-based analysis.
- `date`
- `year`
- `month`
- `month_name`
- `year_month`

---

## 🛠 Tools & Technologies Used

| Tool | Purpose |
|----|----|
| **SQL** | Data aggregation, KPI calculation, performance analysis |
| **Excel** | Data validation, pivot tables, exploratory analysis |
| **Power BI** | Operational dashboards and KPIs |
| **Tableau** | Executive storytelling and pattern detection |
| **GitHub** | Version control and portfolio hosting |

---

## 🔄 End-to-End Analytics Workflow

### 1️⃣ Excel – Data Validation & Exploration
- Reviewed raw session data
- Validated revenue and energy calculations
- Created pivot tables to analyze:
  - Revenue by city
  - Sessions by station
  - Charger type performance

---

### 2️⃣ SQL – Core Analysis & KPIs
SQL was used to perform structured analysis:

**Key Analyses:**
- Monthly revenue by city and charger type
- Average charging sessions per station (utilization)
- Revenue efficiency (revenue per kWh)

SQL scripts included:
- `01_monthly_revenue.sql`
- `02_station_utilization.sql`
- `03_revenue_efficiency.sql`

---

### 3️⃣ Power BI – Operational Dashboards
Power BI was used for **structured reporting and KPI tracking**.

**Dashboard Pages:**
- **Executive Summary**
  - Total Revenue
  - Total Energy Delivered
  - Average Revenue per Session
- **City & Station Performance**
  - Revenue by city
  - Station utilization comparison
- **Charger Efficiency**
  - Fast vs Standard charger analysis
  - Revenue per kWh

---

### 4️⃣ Tableau – Executive Storytelling
Tableau was used for **visual storytelling and pattern identification**.

**Key Visuals:**
- Heatmap showing station utilization across months
- City-level revenue comparison
- Trend analysis of Fast vs Standard charger revenue
- Management insights panel highlighting key findings

---

## 📊 Key Metrics Defined
- **Total Revenue**
- **Total Energy Delivered (kWh)**
- **Average Sessions per Station per Day**
- **Revenue per kWh**
- **Revenue Contribution by City**
- **Charger Type Efficiency**

---

## 🧠 Key Insights
- Fast chargers generate **higher revenue per kWh** compared to standard chargers
- Certain stations show **low utilization**, indicating capacity or location issues
- Metro cities contribute a significant share of total charging revenue
- Utilization patterns vary seasonally across cities

---

## 📂 Repository Structure

EV_Charging_Analytics_Project

├── charging_sessions_raw.csv
├── stations_dimension.csv
├── date_dimension.csv
├── EV_Charging_Analytics.xlsx
│
├── 01_monthly_revenue.sql
├── 02_station_utilization.sql
├── 03_revenue_efficiency.sql

## 🚀 Outcome
This project demonstrates:
- End-to-end ownership of a data analytics problem
- Ability to translate raw operational data into business insights
- Hands-on experience with SQL, Excel, Power BI, and Tableau
- Strong understanding of analytics workflows used in real organizations

- <img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/5e726eae-2a09-4189-80ec-6c7c9976e4d9" />

