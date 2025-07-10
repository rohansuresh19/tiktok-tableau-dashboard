# 📱 TikTok Tableau Dashboard – Coursera Project

This repository contains an interactive Tableau dashboard analyzing TikTok video performance data, built as part of a Coursera data visualization project.

🔗 **Live Dashboard:**  
👉 [Click to view on Tableau Public](https://public.tableau.com/app/profile/rohan.suresh6600/viz/TikTokProjectCoursera_17471371209810/BoxplotDashboard)

---

## 🎯 Project Overview

This project explores trends in TikTok video engagement by comparing **claim** and **opinion** content. The goal was to visualize how metrics like views, likes, and author status differ between content types to support content moderation strategies.

### ✅ Key Features

- 📦 **Boxplots**: Visual distribution of  
  - Video Duration  
  - Like Count  
  - Comment Count  
  - View Count  
- 📊 **Claim vs Opinion** Content Distribution  
- 🚫 **Author Ban Status** Breakdown  
- 🎛️ Interactive Filters for Data Exploration

---

## 🔍 Insights Uncovered

- **Claim videos** generally receive **higher engagement** than opinion videos.
- **Banned authors** are more commonly associated with claim content.
- **Verified users** tend to post opinion-based content.
- Outliers were detected in all key engagement metrics using boxplots.

---

## 🧠 PACE Strategy Summary

**Plan:**  
- Variables: `claim_status`, `author_ban_status`, `verified_status`, engagement metrics  
- Units: seconds, counts; some nulls in comment/share count  
- Tools: Descriptive statistics, IQR-based outlier detection, Tableau visuals

**Analyze:**  
- Cleaned and transformed data, no joins required  
- Mixed visuals: boxplots for internal insights, pie/bar charts for broader audience  

**Construct:**  
- Built in Tableau with embedded filters  
- Interactive exploration based on claim status and author type  

**Execute:**  
- Shared via Tableau Public  
- Supported strategic insights for content policy and moderation

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `TikTok Project (Coursera).twbx` | Tableau workbook with full dashboard |
| `tiktok_dataset.xlsx` | Cleaned TikTok dataset used in Tableau |
| `TikTok_EDA_Executive_Summary.docx` | Full project summary with PACE framework |

---

## 🛠 Tools Used

- **Tableau Public** – Dashboard & Visualization  
- **Microsoft Excel** – Initial data prep  
- **Python (Optional)** – For data inspection and plotting  
- **Coursera** – Project submitted as part of Google Advanced Data Analytics specialization

---

📬 **Author:** Rohan Suresh  
🗂️ GitHub: [`@rohansuresh19`](https://github.com/rohansuresh19)

---

> _“Turning raw metrics into meaningful visuals to guide smart decisions.”_
