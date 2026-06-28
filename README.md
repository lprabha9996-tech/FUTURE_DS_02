# 📊 Telco Customer Retention & Churn Optimization Dashboard

An end-to-end business intelligence solution designed to isolate severe customer churn vulnerabilities, analyze early subscriber lifecycles, and deliver data-backed interventions for product and retention leaders. 

This project transforms 7,043 raw subscriber records into a dynamic, executive-ready Power BI tracking engine.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **BI Platform:** Power BI Desktop
* **Data Transformation:** Power Query (Data Type optimization, structural parsing, value mapping)
* **Analytical Modeling:** DAX (Data Analysis Expressions) for Custom KPI Measures
* **Visual Engineering:** Visual filtering, conditional alignment, and executive UI/UX dashboard layout

---

## 🔍 The Core Business Problem

The company is experiencing a baseline **churn rate of 26.5%**, resulting in 1,869 lost subscribers. However, looking at the macro average doesn't solve the problem. This analysis was initiated to answer critical product questions:
1. *When* exactly are we losing our customers?
2. *Which* operational configurations (billing, contracts) introduce the highest friction?
3. *What* product utility features act as natural retention anchors?

---

## 📈 Executive Summary of Key Insights

### 1. The 90-Day Danger Zone (Early Lifecycles)
* **The Cliff:** Customer attrition is heavily front-loaded. **41.9% of all lost subscribers leave within their first 6 months** of tenure, highlighting a critical onboarding or early value-delivery gap.
* **The Stabilization Pivot:** If a user can be successfully guided past the **12-month milestone**, their probability of churning drops below **5%**, transitioning them into highly stable, predictable revenue.

### 2. High-Risk Operational Frictions
* **The "Deadly Combo":** Subscribers on short-term **Month-to-Month plans** who pay via manual **Electronic Checks** exhibit an astronomical churn rate of **53.7%**. More than half of this segment abandons the service, showing that manual billing notifications serve as recurring cancellation triggers.
* **Pricing Elasticity:** Churned users left with a significantly higher average monthly bill (**$74.44**) compared to retained loyal users (**$61.27**), proving pricing sensitivity spikes if platform utility isn't felt.

### 3. Product Utility as a Retention Shield
* **The Support Gap:** Users without *Tech Support* or *Online Security* features churn at an isolated rate of **41.6%**. 
* **The Anchor Effect:** Activating **Tech Support drops churn to 15.2%**, while activating **Online Security slashes it to 14.6%**, proving that foundational security add-ons effectively double platform stickiness.

---

## 🚀 Data-Driven Strategic Playbook

Based on the dashboard architecture, the following three targeted interventions are recommended for the retention team:

1. **Erase Billing Friction:** Deploy a targeted marketing campaign offering a one-time **$5 account credit** to seamlessly migrate manual Electronic Check users onto automated payment tracks (Credit Card or Bank Auto-Pay).
2. **De-risk Month-to-Month Contracts:** Identify short-term accounts at Month 3 (the peak volatility window) and trigger automated in-app offers inviting them to upgrade to an annual plan for a **10% monthly discount**.
3. **Proactive Support Onboarding:** Automatically attach a free 30-day trial of *Tech Support* and *Online Security* features to premium Fiber Optic signups to ensure early product adoption and flatten the early attrition curve.

---

## 📂 Repository Structure

* `/dataset`: Contains the raw anonymized customer records used for ingestion.
* `/dashboard`: Features high-resolution screenshots and layouts of the finalized workspace.
* `key_insights.md`: A deep-dive document highlighting granular segmentation metrics and technical takeaways.
