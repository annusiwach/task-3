# Task 3: Interactive Dashboard Build & RFM Customer Analytics

## 📌 Project Overview
This repository contains the interactive Power BI dashboard designed as part of the data analytics lifecycle for retail transactional performance. The core objective of this dashboard is to synthesize raw transactional records into high-impact, actionable executive insights—bridging the gap between granular customer metrics and high-level retail strategy.

---

## 🎨 Visual Identity & UI/UX Strategy

### 1. Executive Color Palette & Theme
To prevent visual fatigue and ensure high contrast during presentations, a modern **Executive Dark Theme** was developed:
* **Canvas Background:** Deep Navy / Dark Charcoal Blue for a premium enterprise feel.
* **KPI & Grid Containers:** Uniform dark panels outlined with thin, soft gray borders to maximize spatial structure.
* **Typography:** Crisp white text (`#FFFFFF`) and silver labels ensure an accessible, high-contrast ratio.

### 2. Strategic RFM Segment Coding
Instead of a monochromatic block design, the Customer Segment Treemap applies an intentional functional color matrix to prioritize operational focus:
* **Champions / Loyal:** Vibrant Emerald Teal — Signals top-tier brand health and primary revenue drivers.
* **Recent New Customers:** Bright Sky Blue — Highlights a fresh, incoming growth pipeline.
* **At Risk / Can't Lose Them:** Radiant Coral/Amber — Acts as an immediate visual flag for high-priority marketing intervention.
* **Hibernating / Dormant:** Muted Slate Gray — Intentionally recedes into the background layout.

---

## 🛠️ Feature Engineering & Dashboard Architecture

### 1. Unified Control Banner (Slicers & Filters)
* **Dynamic Time Intelligence:** A compact, transparent "Between" Date Slider allows stakeholders to easily restrict data to specific fiscal quarters or operational periods.
* **Category Selection Buttons:** Re-engineered raw dropdown menus into a streamlined horizontal button deck for effortless item filtering.
* **Geographic Matrix Grid:** An intuitive tile matrix that isolates local brick-and-mortar storefront performances (e.g., Bengaluru, Hyderabad, Kolkata) with a single click.

### 2. High-Impact KPI Row
All high-level cards have been stripped of technical data jargon and mapped to professional retail indicators:
* `Sum of total_sales` ➡️ **Total Gross Revenue**
* `Sum of quantity` ➡️ **Total Units Sold**
* `Average_Order_Value` ➡️ **Average Order Value (AOV)**

### 3. Deep-Dive Analytical Visuals
* **Gross Revenue Over Time:** A smoothed, gradient-filled line chart showing the monthly distribution of sales, highlighting key transactional volatility points in the calendar year.
* **Cross-Tab Performance Matrix:** A custom, dark-themed matrix breaking down metrics down to the cross-section of product categories (Chairs, Laptops, Mobiles) and demographic averages (Average Age).

---

## 🕹️ Interactivity & Verification
This dashboard is fully optimized with **Cross-Filtering Interactivity**. 
* Selecting a customer cohort box (e.g., *At Risk*) automatically filters the entire report view—instantly recalculating the total revenue loss, units sold, and pinpointing the exact months where those specific cohorts stopped making active purchases.

---

## 📂 Deliverables Contained In This Folder
* 📄 `Retail_Performance_Customer_Segmentation_Task3.pbix` — The master Power BI report file containing data connections, relationship mappings, and design canvases.
* High-resolution snapshot of the default executive view.
<img width="1083" height="580" alt="Screenshot 2026-07-08 150234" src="https://github.com/user-attachments/assets/2f4e719d-e982-495e-8bcb-3bc613f932f5" />

*Screenshot demonstrating active cross-filtering and segment drill-downs.
<img width="1135" height="588" alt="Screenshot 2026-07-08 152607" src="https://github.com/user-attachments/assets/5c10f000-d9da-4867-b775-c1134e0ab737" />

