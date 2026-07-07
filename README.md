# E-Commerce Sales Performance & Target Tracking Dashboard

An interactive Power BI dashboard engineered to analyze multi-million row retail transactional data, track cross-category sales metrics, map geographical distribution patterns, and directly measure performance benchmarks against dynamic sales targets.

## 📊 Dashboard Preview
*(Tip: Take a snippet/screenshot of your dashboard, save it as `dashboard.png` in your GitHub repository, and link it right below)*
![Sales Performance Dashboard](dashboard.png)

---

## 🚀 Key Features & Analytical Insights

### 1. High-Level Performance KPIs
* **Order Count:** Tracks total order volume (~2K total transactions) to understand store velocity.
* **Sales Revenue & Target Comparison:** Instantly captures aggregate performance ($432K total sales) contrasted side-by-side with overall objectives and the minimum set targets ($9K) across key focus regions.
* **Segment Deep Dives:** Displays a localized view highlighting top regional success markers (e.g., Average Profit in Delhi: 43.31).

### 2. Profitability & Sales Distribution (Product Breakdown)
* **Profit Margin by Sub-Category:** An interactive donut chart mapping high-to-low margin sub-categories like *T-shirts, Accessories, Shirts, Handkerchiefs, Stoles, and Leggings*.
* **Sales Distribution Treemap:** A structural nested tile visual classifying `sales revenue by Category` (Electronics, Clothing, Furniture) into size-proportional distribution squares.
* **Performance Matrix (Pivot View):** A comprehensive matrix breaking down sales numbers chronologically by Year (2018 vs. 2019) across operational lines.

### 3. Advanced Geospatial & Predictive Insights
* **Geographic Sales Mapping:** Live map integration utilizing Bing Maps API to track geographic orders by city, displaying proportional bubble scaling to isolate regional hot spots.
* **Order Count Funnel by State:** Funnel chart showing clear customer volume distribution across top-performing states (Madhya Pradesh, Maharashtra, Gujarat, Delhi, etc.) to evaluate market penetration drop-offs.
* **Profit vs. Quantity Scatter Analysis:** A multi-dimensional scatter plot comparing sales volume against total net profits per sub-category to discover high-volume/low-margin anchors vs premium stars.

---

## 🛠️ Tech Stack & Concepts Applied
* **BI Tool:** Power BI Desktop
* **Data Modeling:** Star Schema design implementing 1-to-Many relationships bridging Target tables, Product Dimensions, and Transaction Fact records.
* **Cross-Filter Evaluation:** Configured advanced relationship behaviors (Bi-directional filtering) to eliminate evaluation bottlenecks and repeating matrix artifacts.
* **Geospatial Profiling:** Location categorization and mapping security clearance configurations.

---

## 📂 Project Structure
```text
├── Data/                   # Raw CSV / Excel datasets used for modeling
├── ECommerce_Dashboard.pbix # Primary Power BI project file
└── README.md               # Project documentation
