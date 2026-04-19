<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/6/69/Airbnb_Logo_Bélo.svg" width="80" alt="Airbnb Logo"/>

# 🏠 Global Airbnb Performance Analysis
### A Power BI Dashboard Project

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)](/)
[![Data](https://img.shields.io/badge/Records-53.7M%20Reviews-FF5A5F?style=for-the-badge)](/)
[![Cities](https://img.shields.io/badge/Cities-10%20Global-484848?style=for-the-badge)](/)

<br/>

> *"Turning 279,712 Airbnb listings into actionable intelligence — from 2008 to the COVID-19 era."*

</div>

---

## 📌 Table of Contents

- [📖 Project Overview](#-project-overview)
- [📊 Key Metrics](#-key-metrics)
- [🔍 Dashboard Pages](#-dashboard-pages)
- [💡 Key Insights](#-key-insights)
- [🛠️ Tools Used](#️-tools-used)
- [📂 Project Structure](#-project-structure)
- [🚀 How to Use](#-how-to-use)
- [📸 Dashboard Preview](#-dashboard-preview)
- [🙌 Acknowledgements](#-acknowledgements)

---

## 📖 Project Overview

This project delivers an end-to-end **Global Airbnb Performance Analysis** using **Microsoft Power BI**. It explores the complete lifecycle of Airbnb — from its early days in 2008 through rapid growth, market maturity, regulatory pressures, and the dramatic impact of COVID-19.

The dashboard uncovers trends across **10 major cities worldwide**, examining listings, pricing, ratings, host trust, seasonality, and review behavior to surface insights that drive real business decisions.

---

## 📊 Key Metrics

<div align="center">

| 🏠 Listings | 🌆 Cities | 👤 Hosts | 🏷️ Property Types | ⭐ Reviews |
|:-----------:|:---------:|:--------:|:-----------------:|:---------:|
| **2,79,712** | **10** | **1,82,024** | **144** | **53,72,983** |

</div>

---

## 🔍 Dashboard Pages

### 📄 Page 1 — New Listings Lifecycle

Tracks the evolution of Airbnb listings from **2008 to 2021**, segmented by:

- 🔵 Total Listings
- 🟣 Entire Place
- 🟠 Private Room
- 🩷 Shared Room
- 🟡 Hotel Room

The lifecycle is broken into **6 distinct phases**:

```
INTRODUCTION → GROWTH → MATURITY → DECLINE → REINVENTION → COVID-19
```

> 📌 **Peak year: 2015** — highest number of new listings ever recorded.

---

### 📄 Page 2 — Market Share & Ratings

**Market Share by City (Pareto Chart)**

```
Paris       → 23.1% cumulative
New York    → 36.4%
Sydney      → 48.4%
Rome        → 58.3%
Rio         → 67.8%
Istanbul    → 76.5%
Mexico City → 83.7%
Bangkok     → 90.6%
Cape Town   → 97.5%
Hong Kong   → 100.0%
```

**Average Pricing by Property Type**

| Property Type | Avg Price |
|:-------------|:---------:|
| 🏨 Hotel Room | **$800** |
| 🏠 Entire Place | **$673** |
| 🛋️ Shared Room | **$580** |
| 🛏️ Private Room | **$462** |

**City Ratings (out of 100)**

| Rank | City | Avg Rating |
|:----:|:-----|:----------:|
| 🥇 1 | Mexico City | **94.8** |
| 🥈 2 | Rio de Janeiro | **94.6** |
| 🥉 3 | Cape Town | **94.4** |
| 4 | New York | **93.8** |
| 5 | Rome | **93.5** |
| 6 | Sydney | **93.2** |
| 7 | Paris | **93.1** |
| 8 | Bangkok | **93.0** |
| 9 | Istanbul | **91.1** |
| 10 | Hong Kong | **89.7** |

---

### 📄 Page 3 — Customer Behavior & Trust

**Review Frequency Distribution**

```
86.6% of customers → wrote only 1 review
98.8% of customers → wrote 3 reviews or fewer
1 customer         → wrote 283 reviews! 🤯
```

**Trust Signal Analysis**

| Identity Status | No Profile Pic | Profile Pic |
|:---------------|:--------------:|:-----------:|
| ❌ Not Verified | 0.3% | 32.6% |
| ✅ Verified | 0.1% | **66.9%** |

> 💡 Over **2/3 of all Airbnb hosts** are fully verified with a profile picture.

**Seasonality Trends**

```
🗼 Paris & Rome  →  Peak reviews: April – August (European Summer)
🗽 New York      →  Peak reviews: November – December (Holiday Season)
```

---

## 💡 Key Insights

```
✅ Paris, NYC & Sydney = nearly 50% of total listings
✅ Paris hotel rooms cost 2x more than Airbnb → drives Airbnb dominance
✅ Mexico City & Rio = highest-rated cities globally
✅ Hong Kong & Istanbul = lowest ratings (cleanliness & value score lowest)
✅ 2015 = Airbnb's peak listing year worldwide
✅ COVID-19 halted Airbnb's 2018 reinvention growth by 2019–2020
✅ 86.6% of users review only once — loyalty & repeat usage is limited
✅ 66.9% of hosts are verified with profile pics — high trust ecosystem
```

---

## 🛠️ Tools Used

| Tool | Purpose |
|:-----|:--------|
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) | Dashboard design & data visualization |
| ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white) | Data cleaning & preprocessing |
| ![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat-square&logo=microsoft&logoColor=white) | Custom measures & calculated columns |
| ![Power Query](https://img.shields.io/badge/Power%20Query-F2C811?style=flat-square&logo=microsoft&logoColor=black) | ETL & data transformation |

---

## 📂 Project Structure

```
📦 Global-Airbnb-Performance-Analysis
├── 📊 Airbnb_Dashboard.pbix        ← Main Power BI file
├── 📁 Data/
│   ├── airbnb_listings.csv
│   ├── airbnb_reviews.csv
│   └── airbnb_hosts.csv
├── 📁 Screenshots/
│   ├── page1_listings.png
│   ├── page2_market_share.png
│   └── page3_behavior.png
└── 📄 README.md
```

---

## 🚀 How to Use

```bash
# Step 1: Clone this repository
git clone https://github.com/your-username/Global-Airbnb-Performance-Analysis.git

# Step 2: Open the Power BI file
# → Launch Power BI Desktop
# → File > Open > Airbnb_Dashboard.pbix

# Step 3: Refresh the data source if needed
# → Home > Refresh

# Step 4: Explore the 3 dashboard pages
# → Page 1: New Listings Lifecycle
# → Page 2: Market Share & Ratings
# → Page 3: Customer Behavior & Trust
```

> **Requirements:** Power BI Desktop (free) — [Download here](https://powerbi.microsoft.com/desktop/)


## 🙌 Acknowledgements

- Data sourced from publicly available **Inside Airbnb** datasets
- Built as part of a **Data Analytics Portfolio Project**
- Inspired by real-world business intelligence use cases in the hospitality industry

---

<div align="center">

**⭐ If you found this project useful, please star this repository!**

[![GitHub Stars](https://img.shields.io/github/stars/your-username/Global-Airbnb-Performance-Analysis?style=social)](/)
[![GitHub Forks](https://img.shields.io/github/forks/your-username/Global-Airbnb-Performance-Analysis?style=social)](/)

<br/>

Made with ❤️ using **Power BI**

</div>
