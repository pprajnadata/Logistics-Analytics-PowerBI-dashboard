# SwifTRoute-Logistics-PowerBI-dashboard
Finding KPIs in Delivery, hubs and Driver details
# 🚚 SwiftRoute Logistics Dashboard

### 📊 Project Overview
This project involves the development of an end-to-end **Power BI Logistics Dashboard** designed to monitor and optimize fleet performance, hub capacity, and delivery efficiency for SwiftRoute. The solution translates complex logistics data into actionable insights, enabling stakeholders to track 1,100+ orders across 6 major hubs.

### 🎯 Business Problem & Solution
**The Challenge:** The logistics team needed a centralized view to assess network size, monitor driver delays, and identify aging vehicles prone to breakdowns.
**The Solution:** A multi-page interactive dashboard covering **Hubs, Drivers, and Vehicle** metrics to support workforce planning and fleet readiness.

### 🔑 Key Features & Metrics
* **Executive Overview:** Real-time tracking of **Total Orders (1,169)**, **On-Time Delivery Rate (80.8%)**, **CSAT (89.9%)**, and **Avg Delivery Time (36.38 Hrs)**.
* **Hub Capacity Planning:** Visualized "Orders Processed vs. Hub Capacity" to identify bottlenecks in high-traffic hubs like Houston and Dallas.
* **Driver Performance Analytics:** Scatter plots correlating **Experience vs. Rating** to pinpoint skill gaps and bar charts identifying drivers with the highest delay frequencies for targeted coaching.
* **Fleet Management:** Analysis of **Vehicle Age vs. Breakdowns** and utilization rates by vehicle model (e.g., Freightliner M2, Mercedes Sprinter) to optimize maintenance schedules.

### 🛠️ Tools & Technologies
* **Power BI:** Data visualization, interactive filtering, and bookmark navigation.
* **DAX:** Calculated measures for MoM growth, On-Time Delivery %, and CSAT variance.
* **Data Modeling:** Star schema architecture linking Fact tables (Orders) with Dimension tables (Hubs, Drivers, Vehicles).
