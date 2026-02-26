# Logistics-PowerBI-dashboard
Finding KPIs in Delivery, hubs and Driver details
# 🚚 Logistics Analysis Dashboard

### 📖 Project Overview
The **SwiftRoute Logistics Dashboard** is a comprehensive Power BI solution designed to optimize supply chain performance across Hubs, Drivers, and Vehicles. This project translates raw logistics data into actionable insights, enabling stakeholders to track KPIs like On-Time Delivery rates, Hub Capacity, and Fleet Maintenance risks.

### 🎯 Business Requirements & Solution
I engineered a multi-page report to address specific business needs defined in the BRD:

#### 1. Executive Overview
* **KPI Tracking:** Monitoring **Total Orders**, **On-Time Delivery %**, **CSAT %**, and **Average Delivery Time** with Month-over-Month (MoM) growth/decline metrics.
* **Performance Snapshots:** High-level visibility into total Hubs, Drivers, and Vehicles to assess network size and fleet capacity.

#### 2. Hub Performance & Capacity Analysis
* **Capacity Planning:** Utilized Clustered Column Charts to compare **Orders Processed vs. Hub Capacity**, identifying bottlenecks in high-traffic locations.
* **Efficiency Ranking:** Ranked hubs by performance to pinpoint top-performing vs. underperforming centers.
* **Processing Speed:** Analyzed **Hub Order Processing Time** via Matrix charts to improve turnaround times.

#### 3. Driver Performance & Workforce Planning
* **Skill Gap Analysis:** Correlated **Experience vs. Rating** using Scatter Plots to identify training needs.
* **Delay Tracking:** Identified drivers with the highest delay frequency to enable targeted coaching.
* **Individual Profiles:** Created detailed driver cards showing Hire Date, Years of Experience, Star Rating, and Monthly Deliveries.
* **Trend Analysis:** Visualized monthly trends of orders and on-time delivery percentages to understand seasonal demand.

#### 4. Fleet Management & Maintenance
* **Fleet Readiness:** Monitored **Active vs. Maintenance** vehicle status using Donut charts.
* **Utilization:** Analyzed Total Orders by Vehicle Model (e.g., Freightliner, Mercedes Sprinter) to optimize fleet usage.
* **Breakdown Analysis:**
    * **Age vs. Reliability:** Scatter plots comparing **Vehicle Age vs. Breakdowns** to identify aging assets with high maintenance risks.
    * **Model Reliability:** Compared breakdown frequency across vehicle models and specific vehicle codes to support targeted maintenance actions.

### 🛠️ Technical Stack
* **Power BI Desktop:** Data visualization, bookmark navigation, and interactive filtering.
* **DAX (Data Analysis Expressions):** Calculated complex measures for MoM change, CSAT variance, and On-Time Delivery rates.
* **Data Modeling:** Designed a Star Schema linking Fact tables (Orders, Delays) with Dimension tables (Hubs, Drivers, Vehicles).
