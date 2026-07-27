# Affiliate Acquisition Analytics Dashboard

A 3-page Power BI dashboard simulating end-to-end affiliate marketing analytics for a blockchain hardware wallet company — covering the full funnel from ad impressions through approved conversions, plus affiliate/network profitability analysis.

## 📊 Project Overview

This project analyzes affiliate acquisition performance across multiple dimensions — country, device, campaign type, affiliate network, and traffic source — to answer the kind of questions a Data Analyst (Acquisition) role would own:

- Which affiliates and networks drive the most revenue and profit, and at what cost?
- Where does the acquisition funnel leak the most (impressions → clicks → landing → checkout → purchase → approval)?
- How does conversion and approval rate vary by device, campaign type, and affiliate?
- What's the ROI/ROAS by affiliate, and which partners are worth scaling vs cutting?

## 🗂️ Dashboard Pages

**1. Executive Overview**
High-level KPIs (Net Revenue, Profit, ROAS, ROI, New Customers), revenue trend, revenue by affiliate type/device/country, and new vs returning customer mix.

**2. Affiliate Performance**
Per-affiliate and per-network breakdown — Top 5 affiliates by revenue/ROAS/purchases, approved vs rejected conversions, revenue vs cost scatter, and a full sortable performance table with ROAS/ROI per affiliate.

**3. Acquisition Funnel**
Step-by-step funnel (Impressions → Clicks → Landing Visits → Configurator → Checkout → Purchases → Approved) with drop-off % at each stage, conversion/approval rate by device, campaign type, and affiliate.

## 🔑 Key Insights

- Funnel drop-off is steepest between **Impressions → Clicks (95% loss)**, suggesting top-of-funnel ad targeting or creative is the biggest lever for scale.
- **Approval rate is consistently ~93% across devices, affiliates, and campaign types** — indicating conversion quality is stable regardless of acquisition channel, and the conversion *rate* (13.4%) rather than approval quality is the real optimization target.
- Revenue is fairly evenly distributed across affiliate types (Community, Influencer, Review Site, Cashback, Media, Comparison — all within a 44-47M band), so no single channel dominates; diversification looks intentional rather than risky concentration.
- Top 5 countries (Germany, UAE, Australia, Canada, Singapore) each contribute similarly (22-24M), suggesting geographic performance is well-balanced rather than dependent on one market.

## 🛠️ Tools Used

- **Power BI** (Power Query, DAX measures, data modeling)
- **Python** (pandas, NumPy — data cleaning/preprocessing)
- Data cleaning: null handling in browser/affiliate rating fields, calculated columns for date hierarchies


## 📸 Screenshots

![Executive Overview](<img width="612" height="337" alt="image" src="https://github.com/user-attachments/assets/af0dad6c-ecbe-4a2e-82bd-f14a46318195" />)
![Affiliate Performance](<img width="626" height="344" alt="image" src="https://github.com/user-attachments/assets/6db3b3f0-beff-4d0b-b7c6-496b89b15957" />)
![Acquisition Funnel](<img width="597" height="338" alt="image" src="https://github.com/user-attachments/assets/fe377808-57f5-4c48-8e5a-4f94da6e3f1f" />)


- `Tangem__Market_analytics.pbix` — full Power BI file
- Screenshots of all 3 pages (above)
