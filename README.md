# E-Commerce Business Intelligence & Operations Dashboard

**Live Interactive Dashboard:** [View on Tableau Public]([https://public.tableau.com/app/profile/christian.aler3008/viz/Ecom2_17786582479070/Categories?publish=yes](https://public.tableau.com/app/profile/christian.aler3008/viz/Ecom2_17786582479070/Categories?publish=yes))

## 📌 Project Overview
This project is an end-to-end e-commerce performance dashboard designed to shift focus from basic operational reporting to strategic business intelligence. Rather than simply tracking "what happened," this dashboard identifies profit drivers, margin killers, and operational bottlenecks to provide actionable recommendations.

The visualizations were built strictly adhering to the **"Storytelling with Data"** methodology, prioritizing cognitive ease, strategic color semantics, and actionable insights over vanity metrics.

## 🧠 Methodology & Design Principles
* **Decluttered Visuals:** Removed gridlines, 3D effects, and unnecessary borders to reduce cognitive load and let the data stand out.
* **Strategic Color Semantics:** * **Primary Blue:** Used exclusively to highlight positive business growth (Profit Margin, Revenue).
    * **Alert Orange/Red:** Used to draw immediate attention to operational friction (High Return Rates, Slowest Delivery Times).
* **Action-Oriented Metrics:** Shifted from tracking raw return volume to calculating *Return Rates*, immediately highlighting which specific product categories require quality control interventions.
* **Dynamic YoY Comparisons:** Engineered robust calculated fields to handle null/zero values cleanly, ensuring precise Current Year (CY) vs. Previous Year (PY) trend tracking without visual flatlines.

## 💡 Key Business Insights Revealed
1.  **The E-Wallet Dominance:** Analysis of payment methods reveals that local e-wallets (Maya, GCash) significantly outperform traditional credit cards and COD in driving revenue. This validates the need to prioritize frictionless digital payment integrations.
2.  **Category Margin vs. Quality:** While categories like Home & Living drive significant growth, a sorted leaderboard analysis isolates specific categories (like Fashion and Beauty) as having the highest return rates, signaling a need for better sizing charts or supplier reviews.
3.  **AOV vs. Order Volume Dynamics:** Top-line KPIs highlight critical shifts in consumer behavior, allowing the business to balance strategies between driving order frequency and increasing Average Order Value (AOV).

## 🛠️ Technical Implementation
* **Tool:** Tableau Public
* **Techniques Used:**
    * Advanced Calculated Fields (Null handling for accurate time-series plotting)
    * Diverging Bar Charts (for Category Growth vs. Baseline)
    * Sorted Horizontal Leaderboards (for immediate operational triaging)
    * Pre-attentive Attribute Styling (Color and positioning to guide executive focus)

---
*Built by Christian | [Interactive Portfolio](https://ckaportfolio.vercel.app)*
