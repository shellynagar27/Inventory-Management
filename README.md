# 📦 Inventory Management Analysis

A Power BI project that analyzes key aspects of inventory operations, including stock levels, supplier performance, restocking patterns, pricing insights, and warehouse utilization. The goal is to uncover actionable insights that can help optimize restocking strategies and improve overall supply chain efficiency.

- [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDEzYThlMjItNmJiMC00ZWQ1LWE3YzQtYWNhNTZjNDZkNWMyIiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9)
- [Linkedin Post](https://www.linkedin.com/feed/update/urn:li:groupPost:12751070-7315424568930656257/)
- [Detail about the challenge](https://zoomcharts.com/en/microsoft-power-bi-custom-visuals/challenges/fp20-analytics-april-2025)

---

## 🚀 Project Overview

This dashboard provides a detailed view of inventory performance through intuitive visuals and metrics. It addresses questions around:

- Stock availability and reorder points  
- Supplier lead times and restocking efficiency  
- Product pricing and turnover analysis  
- Warehouse and geographic distribution of inventory  

---

## 📁 Dataset Overview

The dataset includes fields related to product details, stock levels, suppliers, warehouse locations, restock dates, and pricing. It was used to answer business-critical questions like identifying out-of-stock items, understanding restock cycles, and analyzing warehouse-level stock distribution.

---

## 🛠️ Tools & Technologies Used

- **Python**: For initial data exploration and validation  
- **Power BI**: For data modeling, DAX calculations, and dashboard creation  
- **Power Query**: For data transformation and table creation  
- **Figma**: For dashboard wireframing and color theme planning  

---

## 🔄 Process & Methodology

1. **Data Exploration (Python)**  
   - Performed initial dataset exploration  
   - No null or missing values were found  

2. **Data Preparation (Power Query)**  
   - Created supporting tables like Calendar using query parameters  
   - Defined necessary relationships for data modeling  

3. **Wireframing & Storytelling (Figma)**  
   - Designed wireframe to plan dashboard layout  
   - Selected a consistent color theme for visual clarity  
   - Ensured data storytelling remained focused and relevant  

4. **Measure Creation & Dashboard Development (Power BI)**  
   - Built DAX measures to answer the provided business questions  
   - Designed interactive visualizations and KPIs aligned with the wireframe  

---

## 📊 Dashboard Preview
![Screenshot 2025-04-08 231518](https://github.com/user-attachments/assets/ca7c99ff-3dd0-470b-a775-dfaa01f9b3cd)

![Screenshot 2025-04-08 234538](https://github.com/user-attachments/assets/6f6691d8-1a2d-4680-a36b-74fccb1704fa)

![Screenshot 2025-04-08 234556](https://github.com/user-attachments/assets/0e16fb80-240e-4eee-9676-09f08e48c604)


---

## 🔍 Key Findings

- **Stock Analysis:**
  - *Home & Garden* category has the highest stock quantity (~381K units), while *Electronics* has the lowest (~328K units).
  - 262 products currently fall below their reorder point, indicating a need for timely restocking.

- **Supplier Performance:**
  - *Supplier SUP041* has the highest average lead time (~121 days), primarily for *Books* and *Toys* categories.
  - The shortest lead time is from *Supplier SUP050* (~85 days), suggesting better restocking efficiency.

- **Restocking Patterns:**
  - Restocking spikes were observed in **Sep 2024**, **Oct 2023**, and **May 2025**, hinting at potential seasonal trends.
  - Products marked "Out of Stock" have an average of **202 days** since last restock—indicating a critical delay.

- **Cost & Turnover Analysis:**
  - Top 5 most expensive products are priced above $999, spanning categories like *Books*, *Home & Garden*, *Office Supplies*, and *Electronics*.
  - *Home & Garden* has the fastest stock turnover rate, while *Electronics* shows the slowest.

- **Warehouse & Geography:**
  - *Germany* stores the most products (~533 SKUs), with a concentration in *Sports & Toys*.
  - Country-level stock patterns vary by product category, useful for regional logistics planning.

---

## 💡 Recommendations

- **Optimize Reordering Strategy:**  
  Focus on replenishing products below reorder points to avoid lost sales and customer dissatisfaction.

- **Review Supplier Contracts:**  
  Reevaluate suppliers with long lead times (e.g., SUP041) and consider diversifying sources to reduce restock delays.

- **Prepare for Seasonal Demand:**  
  Leverage historical restocking data to forecast inventory needs during peak months and avoid stockouts.

- **Monitor High-Cost SKUs:**  
  Track high-value inventory closely to manage pricing, reduce holding costs, and align with customer demand.

- **Improve Warehouse Efficiency:**  
  Balance stock distribution across warehouses to avoid overstocking in specific regions and optimize logistics.

---

## 🚀 Business Impact & Dashboard Utility

This Power BI dashboard serves as a dynamic decision-support tool for supply chain and operations teams by:

- Providing **real-time visibility** into stock levels and reorder status
- Helping identify **bottlenecks in restocking** by supplier or location
- Offering insights into **seasonal trends** and **stock turnover rates**
- Supporting **data-driven negotiations** with suppliers based on performance
- Enhancing **warehouse planning** through geographic and category-based stock insights

The dashboard can be used by:
- **Inventory Managers** to ensure product availability and reduce stockouts
- **Procurement Teams** to track supplier efficiency and improve sourcing strategies
- **Logistics Teams** to optimize warehouse space and reduce excess inventory
- **Business Leaders** to monitor KPIs and make strategic supply chain decisions

---

## 📌 Learnings & Takeaways

- Importance of wireframing before building dashboards  
- Efficient use of Power Query and parameters improves model flexibility  
- Clear storytelling prevents dashboard clutter and enhances user experience  

