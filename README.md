# VoltRide: EV Ride-Hailing Operations Optimization  
### DecodeX 2026 Business Case Study

This repository contains our end-to-end analysis for the DecodeX 2026 business case competition.  
The objective of this project was to diagnose operational bottlenecks in an electric vehicle ride-hailing platform and propose data-driven strategies to improve fleet readiness, reliability, and scalability.

---

## 📌 Problem Context

VoltRide operates an EV-based ride-hailing fleet in urban markets where demand is highly time-compressed and operational readiness is influenced by charging behavior, infrastructure access, and fleet distribution.

Unlike conventional ride-hailing systems, EV operations introduce:
- Charging downtime constraints  
- Queueing effects at charging stations  
- Battery-dependent dispatch readiness  
- Spatial supply imbalances across zones  

The challenge was to determine whether fulfillment gaps were driven by **insufficient demand, inadequate fleet size, or operational coordination issues**.

---

## 🎯 Project Objective

The goal of this analysis was to:

- Identify demand–supply stress windows at zone-hour level  
- Decompose cancellation drivers and readiness constraints  
- Detect spatial inefficiencies in fleet deployment  
- Evaluate infrastructure-driven downtime effects  
- Translate analytical findings into actionable business strategies  

---

## 🔍 Key Insights

The analysis revealed that VoltRide’s challenge is **not fleet shortage**, but a gap between registered vehicles and dispatchable supply during peak windows.

Major findings include:

- Peak-hour demand compression creates timing-based supply stress  
- Charging cycle misalignment reduces charge-ready vehicles during demand spikes  
- Fleet capacity exists but is unevenly distributed across zones  
- Charging queues amplify downtime clusters and service unreliability  

These insights indicate that VoltRide’s growth constraint is primarily **operational coordination**, not market demand or fleet scale.

---

## 💡 Strategic Recommendations

Based on the diagnosis, three interventions were proposed:

1. **Predictive Charging Scheduling**  
   Align charging behavior with forecasted demand peaks to improve readiness.

2. **Dynamic Zone-Based Fleet Rebalancing**  
   Reposition supply using data-driven incentives to reduce spatial mismatches.

3. **Peak-Hour Charging Slot Prioritization**  
   Coordinate with infrastructure providers to minimize queue-driven downtime.

Together, these strategies improve fulfillment reliability without immediate fleet expansion.

---

## 🛠 Tools & Methods Used

- Python (Pandas, NumPy, Matplotlib)
- Exploratory Data Analysis & aggregation modeling
- Operational diagnostics at zone–hour level
- Readiness-based supply evaluation
- Business operations frameworks for decision translation

---
## 📂 Repository Structure
├── VoltRide_Analysis_DecodeX.ipynb # Data analysis notebook

├── DecodeX2026_Round2_VoltRide_TeamAquagemi.pdf # Final case report

├── README.md

---

## 🧠 Skills Demonstrated

- Data-driven operational diagnosis  
- Translating analytics into business strategy  
- Demand–supply synchronization analysis  
- Infrastructure constraint modeling  
- Business communication & consulting-style reporting  

---

## 📎 About DecodeX

DecodeX is a national-level business analytics and case competition focused on solving real-world operational and strategic challenges using structured reasoning and data insights.

---

## 👥 Team

**Team Aquagemi**

- Rishav Kumar Shrivastava  
- Saumya Shukla  
- Priyanshu Sekhar Bhuyan  

---

## ⭐ If you find this project interesting

Feel free to explore the notebook, read the report, or use the approach as a reference for EV fleet analytics and operational strategy modeling.

