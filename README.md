# 📦 Supply Chain MIS Dashboard (Excel)
## 🔍 Project Overview

This project is a **Supply Chain MIS & Reporting dashboard** built in **Microsoft Excel**, designed to simulate how a real-world supply chain organization tracks performance, identifies risks, and supports decision-making across products, inventory, orders, suppliers, and manufacturing.

The dataset is structured to represent a mid-sized supply chain operation and is analyzed through **four interconnected dashboards:**

- Product Dashboard

- Inventory & Orders Dashboard

- Supplier & Manufacturing Dashboard

- Executive Summary Dashboard

The focus of this project is **business insight generation**, not just visualization.

---

## 🎯 Business Objectives

The dashboards are designed to answer core operational and managerial questions such as:

- Which products and SKUs drive profit and inventory risk?

- Where are inventory shortages and fulfillment delays occurring?

- How do suppliers compare when volume, cost, defects, and lead time are considered together?

- What is the overall health of the supply chain at an executive level?

---

## 🧱 Dataset Structure

The dataset contains integrated supply chain data covering:

- **Product data:** SKU, category, price, availability, sales, revenue

- **Inventory & orders:** stock levels, order quantities, fulfillment times, inventory deficits

- **Logistics:** shipping carriers, transportation modes, shipping costs, shipping time

- **Suppliers & manufacturing:** production volumes, lead time, manufacturing cost, inspection results, defect rates

- **Profitability:** costs vs profit by SKU and supplier

Data consistency checks were performed:

- Datatypes validated (numeric, categorical, date fields)

- Negative inventory values interpreted as inventory deficits

- Derived columns created for KPIs and ratios

---
## 🖼️ Dashboard Preview

<img width="989" height="477" alt="image" src="https://github.com/user-attachments/assets/d3db4dff-7027-4197-8cb0-b3e3975bcece" />   <img width="1169" height="476" alt="image" src="https://github.com/user-attachments/assets/9270c19b-10e9-4e95-a45a-4c6eee03c5d1" />

<img width="1168" height="489" alt="image" src="https://github.com/user-attachments/assets/dbdd6248-9240-4f9a-ba21-4d60971e893b" />  <img width="1505" height="551" alt="image" src="https://github.com/user-attachments/assets/3c9bd8f6-9af2-4cb9-8a31-a94ff68af925" />



---

## 📊 Dashboard Breakdown
### 1️⃣ Product Dashboard

**Purpose:** Understand product-level performance and contribution.

Key insights:

- SKU-wise profit contribution

- Product category performance

- Demand vs availability relationship

- Identification of high-selling but low-availability SKUs

Design choice:

- Tree maps and contribution charts are used to highlight **relative importance**, not just totals.

### 2️⃣ Inventory & Orders Dashboard

Purpose: Identify inventory risk, fulfillment bottlenecks, and demand pressure.

Key insights:

- Inventory deficit analysis by SKU

- Lead time vs inventory position (scatter analysis)

- Pareto analysis of inventory shortages

- Order quantity vs stock availability comparison

Business framing:

- Scatter plots are used to identify **high-risk SKUs** (low inventory + high lead time)

- Pareto logic highlights the few items causing most inventory stress

### 3️⃣ Supplier & Manufacturing Dashboard

**Purpose:** Evaluate supplier performance holistically.

Key insights:

- Supplier comparison across:

- Manufacturing lead time

- Production volume

- Manufacturing cost

- Defect rates and inspection outcomes

- Transportation cost by route and mode

- Manufacturing efficiency KPI with target benchmarks

Important consideration:

- Defect rates are interpreted **in context of production volume** to avoid   penalizing high-volume suppliers unfairly.

### 4️⃣ Executive Summary Dashboard

Purpose: Provide a leadership-level view of supply chain health.

Key insights:

- On-time delivery performance

- Sell-through rate

- Inventory position movement (waterfall)

- Bottleneck identification (peak lead times and costs)

- Pareto analysis of inventory deficits

This dashboard answers:

> “Where should management focus attention right now?”

---

## 📐 Key KPI Definitions

- **On-Time Delivery %**
  
  % of orders where shipping time ≤ lead time

- **Sell-Through Rate**
  
  Products sold ÷ (Products sold + Current inventory)

- **Manufacturing Efficiency**
  
  Production output relative to manufacturing lead time
  Benchmarked against a defined target

- **Inventory Deficit**
  
  Negative inventory balance indicating unmet demand

- **Defect Rate**
  
  Average defect percentage from inspection results

All KPIs are benchmarked or contextualized to avoid standalone averages.

---

## 🛠 Tools & Techniques Used

- Microsoft Excel

- Pivot Tables & Pivot Charts

- Advanced Excel formulas (SUMPRODUCT, cumulative logic, KPI calculations)

- Slicers for interactive filtering

- Waterfall, Pareto, Scatter, Combo, Tree Map, and KPI Gauge charts

- MIS-style dashboard layout and design principles

---

## ⚠️ Assumptions & Limitations

- Dataset is simulated for learning and demonstration purposes

- Category count limits depth in some Pareto analyses

- Time-series analysis is limited due to lack of date granularity

These limitations are acknowledged and compensated for through strong business framing.

---

## 👤 Intended Audience

- Recruiters evaluating MIS / reporting skills

- Hiring managers for Supply Chain, Operations, and Analytics roles

- Analysts seeking real-world Excel dashboard examples

---

## 🚀 Key Takeaway

This project demonstrates the ability to:

- Translate raw supply chain data into **actionable insights**

- Design dashboards aligned with **real business decision-making**

- Apply MIS thinking rather than only visualization skills

---

#### 📌 Feedback and suggestions are welcome.

---
