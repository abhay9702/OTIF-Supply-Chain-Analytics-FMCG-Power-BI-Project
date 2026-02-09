# 🚚 Vanguard FMCG: Strategic Supply Chain Optimization

## 📊 Executive Summary

This repository contains an end-to-end Supply Chain Analytics solution developed in Power BI. The project focuses on resolving critical service-level gaps for a growing FMCG manufacturer by tracking real-time delivery performance against aggressive business targets.

---

## 🚩 The Business Challenge

**Vanguard FMCG**, a prominent manufacturer based in Gujarat (operating in Surat, Ahmedabad, and Vadodara), is preparing for a nationwide expansion into Tier-1 metros over the next 24 months.

However, the expansion is currently stalled due to **contract renewal failures**. Several key clients have declined to extend annual agreements, citing consistent service inconsistencies. Stakeholders suspect a breakdown in the "Perfect Order" cycle—specifically regarding delivery timelines and quantity completion.

### The Objective

To secure the expansion, management requires a robust tracking system to monitor:

* **Reliability:** Are products arriving when promised?
* **Completeness:** Are orders being filled entirely?
* **Efficiency:** How often do we achieve the "Perfect Order" (On-Time & In-Full)?

---

## 🛠️ Technical Implementation: Approach

As the Lead Data Analyst on this project, I implemented a standard industry framework to quantify service levels daily.

### 1. Core Key Performance Indicators (KPIs)

I developed DAX measures to track the following metrics against pre-defined customer service level agreements (SLAs):

* **OT % (On-Time Delivery):** Percentage of orders received by the customer within the promised window.
* **IF % (In-Full Delivery):** Percentage of orders where the quantity delivered matches the quantity ordered.
* **OTIF % (On-Time In-Full):** The "Gold Standard" metric—orders that were both on time and 100% complete.

### 2. Dashboard Architecture

The interactive Power BI suite was designed to provide:

* **Executive Overview:** High-level status of OTIF vs. Targets.
* **Product Insights:** Granular performance tracking of specific SKUs (Dairy, Food, Beverages).
* **Geographic Analysis:** Performance comparison across Surat, Ahmedabad, and Vadodara.
  
<img width="990" height="552" alt="Screenshot 2026-02-09 143829" src="https://github.com/user-attachments/assets/800ed509-d08a-4866-acd7-5991eb57baa0" />

<img width="990" height="552" alt="Screenshot 2026-02-09 143842" src="https://github.com/user-attachments/assets/0c030634-d781-4cd9-a86d-795cfaaca992" />

<img width="990" height="552" alt="Screenshot 2026-02-09 143856" src="https://github.com/user-attachments/assets/93efde65-627d-49f6-af83-23bba2434b91" />

<img width="990" height="552" alt="Screenshot 2026-02-09 143923" src="https://github.com/user-attachments/assets/923fd0e2-a136-4c54-afd1-d7b6e2cae7aa" />

## 💡 Key Insights Derived

* Identified a **15% lag** in OTIF performance for the "Dairy" category during weekend surges.
* Discovered that **Ahmedabad** consistently outperforms other cities in "In-Full" metrics but struggles with "On-Time" arrivals due to local logistics bottlenecks.
* Products are not being delivered in full ordered quantity.
* All the perfomance metrics(OT%, IF%, OTIF%) are below the target, the mart supply chain is not performing good.
* Line Fill Rate is 65.96%, it means many of the orders are not being delivered in full quantity.
* Volume Fill Rate is around 96%, it means there is 4% difference in the quantity of items when they reached the customers.
* Root Cause Identification: Isolated a consistent 30% delay rate in specific product categories.
* There is a big in IF% vs Target for most of the customers. Is it because of less production?
* Lotus Mart, Coolblue and Acclaimed Stores are among the customers with highest number of orders but also most delayed delivery rate.

