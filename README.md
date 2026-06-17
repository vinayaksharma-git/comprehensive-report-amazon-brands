# Comprehensive Sales Report of Brands Listed on Amazon

A dynamic Power BI data visualization and business intelligence project designed to analyze and evaluate the sales performance, market penetration, year-over-year (YoY) growth, and customer sentiment of various brands listed on Amazon between **2023 and 2026**.

---

## Project Overview
This project processes transaction, product, and review data to extract deep business insights. The interactive Power BI dashboard assists stakeholders in understanding volume drivers, tracking financial revenue, isolating geographical performance trends, and correlating consumer ratings with sales metrics.

---

## Dashboard Pages & Feature Breakdown

The report is divided into several analytical modules accessible via the navigation tabs:

### 1. Brand-Quantity Analysis (`Brand-Quantity`)
* **Visual Type:** Treemap Chart (Hierarchical structure breakdown).
* **Key Insight:** Evaluates the **Sum of Quantity** sold, broken down by Parent Brand down to specific Product Names.
* **Highlight:** Apple captures a significant share of transaction volume, with specific high-performing accessories like the *Apple Accessorie Stand* highlighted as top product volume drivers.

### 2. Total Quantity & Country Distribution (`TotalQuantity`)
* **Visual Type:** Matrix Table & Sorted Clustered Bar Chart.
* **Key Insight:** Displays global distribution of order quantities. 
* **Highlight:** The **United States (US)** leads global market demand significantly with **846 units**, followed by Great Britain (GB - 213 units) and Canada (CA - 153 units). 

### 3. Financial Performance Breakdown (`Brand-TotalAmount`)
* **Visual Type:** Large-scale Treemap.
* **Key Insight:** Segments total gross revenue (**Sum of total_amount**) generated across the catalog.
* **Highlight:** While certain products may have lower transaction quantities, financial high-ticket items like Apple smartphones, laptops (*Apple Book4 Ultrabook*), and smart home products (*Instant Pot Microfiber Kitchenware*) occupy the largest financial footprint of the platform's **$129.51K** total revenue.

### 4. Sales Trends & YoY Growth (`Sales&Growth`)
* **Visual Type:** Growth Matrix & Waterfall Trend Chart.
* **Key Insight:** Evaluates temporal revenue growth over years (2023–2026) using customized DAX expressions.
* **Core Logic Included:** Tracks financial momentum using comparative periodic analysis metrics.

### 5. Customer Sentiment & Ratings (`Count-of-Rating`)
* **Visual Type:** Horizontal Bar Chart, Matrix Summary, and Gauge Indicator.
* **Key Insight:** Compares brand popularity based on user interaction frequency and review submissions.
* **Highlight:** Features a high platform-wide customer satisfaction score with an **Average Rating of 4.05 / 5.00**. Brands like *Wilson*, *Apple*, and *Nike* hold the highest volume of consumer ratings.
