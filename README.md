## Dashboard Preview

![Executive Summary](screenshots/executive-summary.png)

![Vendor Drill-Down](screenshots/vendor-drilldown.png)

# 📊 Vendor Risk Scoring & BI Diagnostics

A validated, multi-factor vendor risk-scoring model and analytics framework built on a simulated procurement dataset consisting of 60 unique suppliers and over 3,000 corporate purchase orders.

## 🎯 The Business Problem
Procurement managers often lack data-driven clarity on vendor failure points until bottlenecks hit factory floors. This project transforms raw purchase history into predictive risk tiers, isolating systemic supply chain vulnerabilities before they escalate into production halts.

## 🛠️ Tech Stack & Methods
- **Core Modeling:** Microsoft Excel (`AVERAGEIFS`, `SUMIFS`, `INDEX/MATCH`, and automated data integrity validations).
- **Business Intelligence:** Microsoft Power BI Dashboard (Star-schema data architecture, custom DAX metrics, and structural drill-down layers).

## 🧠 Validated Architecture & Insights
- **The Validation Run:** To test the mathematical model's accuracy, 6 intentional problem vendors were secretly seeded into the source data. The calculation formulas successfully isolated and surfaced **4 out of the 6 target problem vendors** inside the top 8 highest risk slots.
- **Key Domain Insight:** Operational risk profiles do not cluster cleanly by product category; risk is a localized, vendor-level property that macro-level 'blanket category policies' fail to resolve.

---

## 🔗 Related Framework Portfolio
> 🚀 **Interactive Companion Application:** See my companion repository [Vendor Risk Diagnostics — Interactive Python App](../Vendor-Risk-Diagnostics-Interactive-Python-App) to inspect this exact supply chain optimization problem solved using a reactive **Python & Streamlit** full-stack software interface.

### Related Project

Related project: see [vendor-risk-supply-chain-diagnostics](https://github.com/arvind-yadav-vit/vendor-risk-supply-chain-diagnostics) for the same problem solved with Python + ML.
