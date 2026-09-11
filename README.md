# Maritime Logistics & Trade Finance Analytics Platform (Kandla & Mundra Ports)

An end-to-end operational intelligence and financial modeling suite engineered in Power BI to track maritime cargo flow, port turnaround, terminal tank storage, and consignment landed cost margins.

---

## 📌 Architecture & Modules

### 1. Vessel Turnaround & Demurrage Risk Analyzer
* **Objective:** Monitors discharge laytime, berth occupancy, and financial demurrage liabilities.
* **Key Metrics:** Turnaround Time (TAT in Hours), Laytime Deficit, Net Demurrage Liability ($).

### 2. Consignment Landed Costing & Margin Analyzer
* **Objective:** Granular costing model factoring in CIF (USD), Forex volatility, Basic Customs Duty, and Port Handling to determine true landed cost per MT.
* **Key Metrics:** Landed Cost per MT (INR), Realized Gross Margin (%).
* **Key Finding:** Low-margin Fuel Oil yields steady cash flows, while Base Oil SN 500 carries severe margin erosion risk from storage penalties.

### 3. Tank Farm Capacity & Inventory Aging Analyzer
* **Objective:** Real-time visibility into tank farm capacity utilization, available ullage, and accrued overstay penalties beyond free storage days.
* **Key Metrics:** Total Capacity (41K MT), Active Stock (25K MT), Available Ullage (16K MT), Accrued Storage Penalty (INR 2.77M).

---

## 🛠️ Tech Stack
* **BI Tool:** Microsoft Power BI Desktop
* **Analytical Modeling:** DAX (Data Analysis Expressions)
* **Data Source:** Cleaned Multi-Factor Excel Pipelines
