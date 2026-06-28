# 🏠 Airbnb Performance Dashboard — Power BI

## 📌 Project Overview

An interactive, 3-page Power BI dashboard analyzing Airbnb 
performance across 10 global cities. Built to uncover insights 
on market growth, pricing competitiveness, host trust, city 
ratings, and seasonal demand patterns.

---

## 📊 Dataset Summary

| Metric         | Value       |
|----------------|-------------|
| Total Listings | 279,712     |
| Cities         | 10          |
| Total Hosts    | 182,024     |
| Property Types | 144         |
| Total Reviews  | 5,373,000+  |

**Cities Covered:**
Paris · New York · Sydney · Rome · Rio de Janeiro ·
Istanbul · Mexico City · Bangkok · Cape Town · Hong Kong

---

## 🗂️ Dashboard Pages

### Page 1 — Market Growth & Listing Trends
Analyzes how Airbnb listings grew from 2008 to 2021 across 
property types, with lifecycle phase annotations.

**Key Visuals:**
- KPI cards (Listings, Cities, Hosts, Property Types, Reviews)
- Area chart: New listings over time by room type
- Lifecycle labels: Introduction → Growth → Maturity → 
  Decline → Reinvention → COVID-19

**Key Insights:**
- Airbnb peaked in new listings in 2015
- Regulations caused a slowdown in 2016–2017
- COVID-19 caused a sharp decline from 2019 onward
- Entire Place listings consistently dominated all room types

---

### Page 2 — Market Share, Pricing & City Ratings
Compares city-level performance across listing volume, 
superhost presence, pricing by room type, and guest ratings.

**Key Visuals:**
- Pareto bar chart: Listings by city (Superhost vs Non-Superhost)
  with cumulative % line
- Horizontal bar chart: Average price by room type vs hotel rooms
- Bar chart: Average rating by city (overall + detailed toggle)

**Key Insights:**
- Paris, NYC, and Sydney account for ~48% of all listings 
  and reviews
- Paris hotel rooms average $800/night vs Airbnb's $673 — 
  a 16% price advantage for guests
- Mexico City (94.8) and Rio de Janeiro (94.6) are the 
  highest-rated cities
- Hong Kong (89.7) and Istanbul (91.1) score lowest
- Cleanliness and value-for-money score lowest across cities

---

### Page 3 — Trust Score & Seasonality
Analyzes host verification levels and monthly review 
distribution across cities throughout the year.

**Key Visuals:**
- Shield infographic: Host trust score matrix 
  (Identity Verified × Profile Picture)
- Stream chart: % of monthly reviews by city across 12 months

**Key Insights:**
- 66.9% of hosts are fully verified with a profile picture
- Only 0.3% are unverified with no profile photo
- Rome and Paris dominate reviews April–August 
  (European summer peak)
- New York spikes in November–December (holiday season)

---

## 🔧 Tools & Techniques

| Area            | Details                                      |
|-----------------|----------------------------------------------|
| Tool            | Microsoft Power BI Desktop                   |
| Data Source     | Inside Airbnb (public dataset)               |
| Data Cleaning   | Power Query — nulls, data types, outliers    |
| Data Modeling   | Relationships across listings, hosts,        |
|                 | cities, and date tables                      |
| DAX Measures    | Avg price, cumulative %, monthly review      |
|                 | share, trust score segments                  |
| Visuals Used    | Area chart, Pareto chart, stream chart,      |
|                 | KPI cards, shield infographic, bar charts    |

---

## 💡 Business Questions Answered

1. How has the Airbnb market grown over time, and what 
   disrupted it?
2. Which cities dominate the platform and why?
3. How competitive is Airbnb pricing vs. hotel rooms?
4. Which cities deliver the best guest experience?
5. How trustworthy is the Airbnb host community?
6. When does demand peak in each city across the year?

---

## 📈 Key Findings Summary

- **Market Peak:** 2015 was Airbnb's highest year for 
  new listings globally
- **COVID Impact:** Sharp decline in listings from 2019, 
  visible across all room types
- **Price Edge:** Airbnb entire homes (~$673) are 
  significantly cheaper than hotel rooms (~$800) in 
  major cities
- **Best Rated:** Mexico City and Rio de Janeiro lead 
  in guest satisfaction
- **Seasonal Demand:** European cities peak in summer; 
  New York peaks in holiday season
- **Host Trust:** Over two-thirds of hosts are fully 
  verified — platform safety is strong

---

 👤 Author : Muhammad Ibtisam
Data Analyst | Power BI · SQL · Python · Excel
🔗 LinkedIn https://www.linkedin.com/in/muhammad-ibtisam-shk/ | GitHub 
