# 🏠 Global Airbnb Performance Dashboard (Power BI)

An interactive Power BI dashboard analysing Airbnb listings, pricing, ratings, reviews and host trust across **10 global cities**.

![Dashboard Preview](images/dashboard-page1.png)

## 📌 Project Overview

This project explores how Airbnb has grown, where it performs best, and what guests value most. The dashboard turns raw listing and review data into a three-page story: **market growth → city performance → customer behaviour & trust**.

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Listings | 279,712 |
| Cities | 10 |
| Hosts | 182,024 |
| Property Types | 144 |
| Reviews | 5,373K |

## 🔍 Key Insights

**Growth & lifecycle**
- New listings peaked in **2015**, dipped in 2016–2017 (tighter local regulations), recovered from 2018, then were cut short by **COVID-19**.
- "Entire place" and "Private room" drive most listings; hotel rooms began increasing from 2018.

**Market share & pricing**
- **Paris, New York and Sydney** make up almost half of all listings and **59%** of reviews.
- Paris leads in listings and reviews. Average price by type: Hotel room $800 · Entire place $673 · Shared room $580 · Private room $462.

**Ratings**
- **Mexico City** and **Rio de Janeiro** are best rated; **Hong Kong** and **Istanbul** are lowest.
- **Cleanliness** and **value for money** score lowest across cities.

**Customer behaviour**
- **86.5%** of reviewers reviewed only once; **98.8%** reviewed 3 times or fewer.
- One reviewer logged 283 reviews, which is flagged as a possible data anomaly.

**Seasonality & trust**
- Paris and Rome dominate reviews from **April to August**; New York rises in **Nov–Dec**.
- **66.9%** of hosts are fully verified (ID + profile picture), and unverified anonymous profiles are just **0.1–0.3%**.

## 🛠️ Tools & Skills Used

- **Power BI Desktop**: dashboard design, interactive visuals, conditional-format heatmap, Pareto charts
- **DAX**: measures and calculated columns
- **Power Query**: data cleaning and transformation
- **Data storytelling**: annotated lifecycle chart with written takeaways

## 📁 Repository Structure

```
├── Airbnb_Dashboard.pbix     # Power BI file
├── Airbnb.pdf                # Exported dashboard (3 pages)
├── data/                     # Dataset (or link to source)
├── images/                   # Dashboard screenshots
└── README.md
```

## ▶️ How to Use

1. Download `Airbnb_Dashboard.pbix`.
2. Open it in **Power BI Desktop**.
3. Use the slicers and the *Overall / Detailed rating* toggle to explore.

Or view the PDF export directly in the repo.

## 👤 Author

**Omkar**
Aspiring Data Analyst / Data Scientist · B.Tech ECE (VTU, 2026)
Skills: Python · SQL · Power BI · Excel

🔗 [LinkedIn](https://www.linkedin.com/in/your-profile) · 📧 your.email@example.com

---
⭐ If you found this useful, feel free to star the repo!
