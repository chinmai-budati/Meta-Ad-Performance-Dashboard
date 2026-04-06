# Meta-Ads-Marketing-Performance-Dashboard

### 1. Meta Ads & Campaign Analytics

A sophisticated Power BI dashboard designed to evaluate the performance of marketing campaigns across Facebook and Instagram. This project focuses on tracking audience engagement, conversion efficiency, and budget optimization through data-driven insights.

### 2. Purpose

The purpose of this dashboard is to provide marketing teams and stakeholders with a centralized view of their digital advertising Return on Investment(ROI). By monitoring real-time KPIs like Click-Through Rate (CTR) and Cost Per Conversion, users can identify high-performing ad sets, minimize wasted spend on underperforming creative, and refine audience targeting strategies to maximize lead generation and sales.

### 3. Tech Stack

The dashboard was built using the following tools and technologies:

* 📊 **Power BI Desktop** – Core tool for building the star/snowflake schema data model and interactive visuals.
* 📂 **Power Query (ETL)** – Used for cleaning raw marketing exports, handling date/time formatting, and merging multi-platform event logs.
* 🧠 **DAX (Data Analysis Expressions)** – Implementation of complex measures such as Year-over-Year (YoY) growth, Rolling Average CPA, and Dynamic Ranking of campaigns.
* 🎨 **Data Visualization** – Utilization of modern UI/UX design principles to ensure metrics are readable and actionable for executive decision-makers.

### 4. Data Source

The project utilizes a comprehensive Marketing Dataset containing:

* **Campaigns Data:** Campaign Id, Campaign Name, Start Date, End dDate, Duration, Total Budget.
* **Users data:** User Id, User Gender, User Age, Age Group, Country,Location, Interests.
* **Ads Data:** Ad Id, Campaign Id, Ad Platform, Ad Type, Target Gender, Target Age, Target Interests.
* **Ad Events Data:** Event id, Ad Id, User Id, Timestamp, Day of Week, Time of Day, Event type.

### 5. Features

#### Business Problem

Digital marketing managers often struggle to reconcile spend across different ad placements. Without a unified dashboard, it is difficult to determine if a high click volume is actually leading to a profitable conversion rate, or if specific platforms (Instagram vs. Facebook) are delivering better value for the same budget.

**Stakeholders need to answer:**

* Which campaign objectives (Awareness vs. Conversion) are yielding the lowest Cost Per Result?
* How does ad frequency affect the degradation of Click-Through Rates (Ad Fatigue)?
* What is the correlation between marketing spend and total revenue generated?

#### Goal of the Dashboard

To provide a performance-centric view of the Meta ecosystem that enables:

* **Budget Optimization:** Identify "money pits" where spend is high but conversions are low.
* **Trend Analysis:** Visualize performance fluctuations over time to align with seasonal market shifts.
* **Platform Comparison:** Compare Facebook and Instagram side-by-side to determine the most effective placement for specific demographics.

#### Walkthrough of Key Visuals

* **KPI Header:** Real-time tracking of Total Spend, Total Conversions, Average CTR, and ROAS (Return on Ad Spend).
* **Performance Over Time (Area/Line Chart):** Visualizes the relationship between Spend and Conversions to ensure they scale proportionally.
* **Audience Breakdown (Bar Charts):** Analyzes which age groups and genders are responding most effectively to the current ad creative.
* **Campaign Leaderboard (Table/Funnel):** Ranks campaigns by efficiency metrics, allowing users to quickly see which ads should be scaled or paused.
* **Interactive Slicers:** Deep-dive filters for Platform, Campaign Status, Objective, and Date Range.

### 6. Business Impact & Insights

* **Reduced CPA:** By identifying and pausing low-conversion ad sets, the overall Cost Per Acquisition can be significantly reduced.
* **Creative Strategy:** Insights into which ad formats (Video vs. Image) drive more engagement allow for more informed content production.
* **Scalability:** Clear visibility into winning audiences provides a roadmap for increasing budget with confidence.

### 7. Screenshot:
![Dashboard Preview](https://github.com/chinmai-budati/Meta-Ad-Performance-Dashboard/blob/main/Ad%20Performance1.png)

![Dashboard Preview](https://github.com/chinmai-budati/Meta-Ad-Performance-Dashboard/blob/main/Ad%20Performance2.png)
