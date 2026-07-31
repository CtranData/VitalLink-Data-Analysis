# VitalLink Operations & Financial Analysis (2024–2025)
## Company Overview

VitalLink is a business-to-business (B2B) healthcare supply chain distributor supplying hospitals, clinics, and outpatient facilities with medical goods across five product categories: Diagnostics, Lab Equipment, Patient Care, Personal Protective Equipment (PPE), and Surgical Supplies. The company manages thousands of orders annually across these categories. 

## Purpose 
This project serves to handle the end-to-end data analyst lifecycle, transforming raw, uncleaned transactional healthcare supply records into business insights to relocate valuable resources in other areas of the company to optimize. Goal is to leverage previous data benchmarks to assess the performance of the company's workflow and form possible suggestions and insights to further improve their margin and results that makes them successful. 

## Data Source
This project uses a synthetic dataset generated to simulate 24 months 
of B2B healthcare supply chain transactions, created with Python 
(via Gemini-assisted prompting) to model realistic order volume, 
pricing, and margin behavior for a mid-size medical distributor.

## Tools & Methodology
* **Data Generation:** Python (VS Code), synthetic data simulating 
  transactional records
* **Data Cleaning & Transformation:** Google Sheets — ARRAYFORMULA, 
  IF, XLOOKUP for record-level cleaning and joins
* **Analysis:** Pivot Tables for monthly aggregation (revenue, gross 
  profit, margin, order volume)
* **Visualization:** Google Sheets native charting

## Core Findings
* **Resilient Profitability:** A time analysis of VitalLink's performance over 2024 and 2025 shows a stable gross profit margin between 27.25% to 28.39%. The company is aligning perfectly within the standard 15% to 30% profit margin benchmark for industrial medical distribution.
* **The Growth Trade-Off:** Sticking strictly to highly conservative, safe risk-management plans potentially caps top-line revenue growth, limiting the massive potential gains that could break VitalLink past its historical average industry baseline.
* **Seasonality:** Total revenue fluctuates, peaking between July and October before softening in Jan-Feb and Nov. The gap between peak and low months is moderate — roughly 8-9% — indicating demand swings are noticeable but not extreme.
* **Operational Predictability:** This multi-year consistency in profit margin proves that VitalLink's current work structure and internal systems produces highly predictable and sustainable results.
* **Sales & Supply Chain Alignment:** Maintaining flat margins over the span of two years indicates that the B2B sales division has a solid pricing strategy and maintains effective communication with internal branches like the supply chain.
* **Category Insights:** Gross margin stays consistent across every product category (27.2% – 29.3%), with Patient Care posting both the highest margin and the highest order volume — indicating margin discipline holds even under high order volume.
* **Volume-Price Relationship:** Order volume and unit price show an inverse relationship — low-volume categories like Surgical Supplies carry premium unit prices ($448 average), while high-volume categories like Personal Protective Equipment and Patient Care sit at much lower unit prices ($8 – $9 average) despite making up the majority of total order quantity.
## Data Visualization
<img width="600" height="371" alt="Revenue Insights" src="https://github.com/user-attachments/assets/66ed9bfd-298a-4fac-855f-c04e205c5ca7" />
<img width="600" height="371" alt="Category Performance" src="https://github.com/user-attachments/assets/3748bad9-75c3-4659-aabf-2c61f7306bad" />
<img width="654" height="404" alt="Order Volume vs Unit Price by Category " src="https://github.com/user-attachments/assets/5c8634ae-d705-4e6f-8472-ddab12133056" />

Points from left to right by volume: Surgical Supplies, Lab Equipment, Diagnostics, Patient Care, Personal Protective Equipment.

## Operational Leverage
* **Proactive Resource Allocation:** VitalLink can leverage this historical data to schedule appropriate warehouse staffing and scale up inventory stock levels prior to peak months, effectively preventing stockouts and meeting high-volume seasonal demand.
* **Slow-Season Inventory Optimization:** Because the winter slowdown is highly predictable, suppliers can actively lower stock overloads during the slow seasons (November to February). This minimizes excess holding costs and allows the company to prioritize its resources into other departments or preserve them for the busy summer and fall push (June to October).

## Strategic Recommendations
* **High-Volume Contract Optimization:** The volume-price shows Personal Protective Equipment and Patient Care holding the highest order volumes (580,502 and 474,756 units respectively) but the lowest average unit prices (~$8–9) — indicating the company already has significant volume leverage in these categories. Introducing strategic sales parameters, such as lowering unit costs for high-volume orders tied to long contracts would help capitalize on this leverage. This strategy assists with ensuring recurring revenue, lowers the rate of denied or canceled orders, and ensures customers are more committed to their payment schedules.
* **Operational Flexibility Premium:** In contrast Surgical Supplies sits on opposite end of the spectrum — low order volume (4,754 units) paired with a premium average unit price (~$448) — suggesting these are lower-frequency, higher-value, likely more specialized orders. Implementing a specialized pricing tier that charges a premium for time-sensitive orders and sophisticated, custom-tailored transactions would let the sales team directly monetize the operational flexibility already implicit in this category's order pattern.

## Limitations
- This dataset is synthetic and simulates plausible business patterns; 
  it does not reflect actual VitalLink transactions or real market 
  conditions.
- The dataset spans 24 months, which limits confidence in multi-year 
  seasonal trend claims — a longer time horizon would strengthen the 
  seasonality findings.
- Margin is analyzed at the aggregate level only; a category-level 
  breakdown (PPE vs. surgical supplies vs. equipment) could reveal 
  variation the top-line number hides.
- Recommendations (contract tiering, flexibility pricing) are 
  hypotheses grounded in the observed patterns, not validated against 
  actual client-level order data.
