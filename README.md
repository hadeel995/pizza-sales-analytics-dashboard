# 🍕 Pizza Sales Analytics Dashboard

An interactive business intelligence project analyzing operational key performance indicators (KPIs), consumer preferences, and sales trends for a commercial pizzeria operation based on historical transactional records.

---

## 📊 Dashboard Overview
<img width="1308" height="423" alt="Screenshot 2026-06-06 154803" src="https://github.com/user-attachments/assets/e750d700-c96d-473f-9314-cb8cb2d3452b" />


The analytics layout functions as a high-fidelity business intelligence engine that aggregates complex transactional data points into clear, actionable visual insights. The user interface allows stakeholders to track inventory needs, optimize staffing hours, and identify high-performing menu items at a glance.

### 📈 Core Business KPIs
* **Total Revenue:** `$8,436` — Cumulative sales value generated across all product categories.
* **Total Orders:** `499` — Distinct customer transactions fulfilled.
* **Total Quantity Sold:** `511` — Total volume of individual pizzas prepared and delivered.

### 🍕 Order Distribution by Pizza Category
* **Visual Representation:** Donut Chart
* **Data Breakdown:** * **Classic:** 149 orders
  * **Veggie:** 134 orders
  * **Supreme:** 122 orders
  * **Chicken:** 94 orders
* **Strategic Value:** Highlights the dominant market share held by Classic and Veggie variations, allowing supply chain managers to prioritize core ingredient procurement.

### 📏 Consumer Size Preference
* **Visual Representation:** Pie Chart
* **Data Breakdown:** * **Large (L):** 47% of total sales
  * **Medium (M):** 27%
  * **Small (S):** 22%
  * **Extra Large (XL):** 3%
* **Strategic Value:** Establishes that nearly half of the consumer base prefers Large-sized pizzas, guiding promotional bundles and box/packaging manufacturing volumes.

### 🏆 Top 10 Pizzas by Quantity Sold
* **Visual Representation:** Horizontal Bar Chart
* **Insights:** Identifies exact menu items driving order volumes, led significantly by **The Classic Deluxe Pizza** (30 units sold) and **The Barbecue Chicken Pizza** (26 units sold), providing clear parameters for menu optimization.

### ⏰ Operational Hourly Trendline (`Total Order by Hour Trendline`)
* **Visual Representation:** Area/Line Graph Combo
* **Insights:** Tracks consumer demand from 11:00 AM through 11:00 PM. 
  * **Lunch Rush:** Peaks at 12:00 PM – 1:00 PM (55–56 orders).
  * **Dinner Peak (Absolute Daily High):** Reaches maximum volume at **5:00 PM** with **72 orders**, before gradually declining into the late evening (dropping to 2 orders by 11:00 PM).
* **Strategic Value:** Informs dynamic kitchen staffing schedules and delivery driver allocation to match high-volume intervals.

### 📅 Monthly Demand Volatility (`Most Active Month - Customer Order`)
* **Visual Representation:** Vertical Column Chart
* **Insights:** Evaluates month-over-month performance over the annual cycle. **June** marks the peak operational month with **54 orders**, followed closely by August (51 orders), while March marks the lowest valley (30 orders).

---

## 🛠️ Interactive Filtering & Slicers
The dashboard includes dynamic multi-select slicers that filter the entire data model instantaneously:
* **Order_Date Timeline Slider:** Allows cross-sectional evaluation across historical months.
* **Pizza_Category Slicer:** Toggle views exclusively for *Chicken, Classic, Supreme,* or *Veggie*.
* **Pizza_Size Slicer:** Isolate micro-metrics for *L, M, S,* or *XL* options.

## 🚀 Technical Implementation Stack
* **Data Modeling & Transformation:** SQL / Power Query
* **Visualization Platform:** Power BI / Excel Analytics 
* **Source Mockup Asset:** `Screenshot 2026-06-06 154803.png`
