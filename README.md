# 🐦 Twitter Engagement Analysis Dashboard

A Power BI project analyzing tweet performance metrics using **DAX** and **Power Query**.  
The dashboard tracks engagement trends, media impact, and time-based visibility with 6 analytical visuals and 4 KPIs.

---

## 📘 Project Overview
This project explores how different tweet attributes — like media, hashtags, links, and app opens — affect engagement.  
Custom logic was applied using **Power Query transformations** and **DAX filters** (even/odd dates, time windows, text cleaning) to create an interactive, insight-driven dashboard.

---

## 📊 Key Visuals

| # | Visual | Objective | Key Conditions |
|---|---------|------------|----------------|
| **1️⃣** | Media vs Non-Media Engagement | Compare engagement & impressions for tweets with/without media | Show only 3–5PM IST, even date, word count > 40 |
| **2️⃣** | Media Engagements vs Media Views | Relationship between views & engagement | Replies >10, engagement rate >5%, 6–11PM, odd date |
| **3️⃣** | Interaction Breakdown | Compare clicks by tweet category (media/link/hashtag) | Clicks >0, 3–5PM, even date |
| **4️⃣** | Text-Based Filtering | Analyze engagement excluding tweets with letters ‘C’, ‘S’, ‘D’ | Text cleaned in Power Query |
| **5️⃣** | High-Media Tweet Comparison | Compare replies, likes, retweets for high media engagement tweets | Jun–Aug 2020, odd date, even media views |
| **6️⃣** | App Opens vs Non-App Opens | Compare engagement rate based on app opens | Weekdays 9AM–5PM, even impressions, odd date, char count >30, exclude ‘D’ |

---

## 🧮 KPI Metrics

| KPI | Description |
|------|--------------|
| **Average Engagement Rate** | Measures overall tweet engagement performance |
| **Total Impressions** | Shows total tweet reach |
| **Average Media Engagements** | Tracks average engagement for tweets with media |
| **App Opens Contribution (%)** | % of engagement from tweets that triggered app opens |

---

## 🧱 Tools & Techniques
- **Power BI Desktop**
- **Power Query (M Language)** for data cleaning  
- **DAX (Data Analysis Expressions)** for filters and measures  
- Conditional **visual visibility** using time logic  
- Interactive **KPI-driven layout**

---

## 📈 Key Insights
- Tweets with **media and hashtags** yield higher engagement.  
- Engagement peaks during **3–5PM** and **7–11PM IST**.  
- **App Opens** strongly correlate with higher engagement.  
- Character-rich tweets (>30) perform better on visibility metrics.

---

## 🪄 Author
**Deepak [MBA – Business Analytics]**  
Data Analytics | Power BI | DAX | Business Intelligence  
📫 Connect on [LinkedIn](#)

---

## 🏷️ Tags
`#PowerBI` `#DAX` `#DataAnalytics` `#Dashboard` `#TwitterEngagement` `#BusinessIntelligence`
