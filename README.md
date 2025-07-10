# TikTok Claims vs Opinions: Tableau EDA Dashboard  
**Coursera Capstone Project — Google Advanced Data Analytics Specialization**  
> _Visual storytelling meets data analytics. A Coursera capstone project exploring TikTok content performance using Tableau and Python._

🔗 **Live Dashboard:**  
👉 [Click to view on Tableau Public](https://public.tableau.com/app/profile/rohan.suresh6600/viz/TikTokProjectCoursera_17471371209810/BoxplotDashboard)

---

## 🎯 Project Overview

This project investigates patterns in TikTok video performance, focusing on the classification of videos as **claims** or **opinions**. The goal was to uncover how engagement metrics such as views, likes, and comments vary by content type — and what that might imply for content moderation or predictive modeling.

---

## 📌 Key Features

📦 **Boxplots showing distribution for:**
- Video Duration  
- Like Count  
- Comment Count  
- View Count  

📊 **Claims vs Opinions comparison by:**
- Engagement metrics  
- Author verification and ban status  

🎛️ **Interactive Filters:**
- Explore relationships between key variables  
- Enable non-technical audiences to interact with insights  

---

## 🔍 Insights & Impact

- 🔺 Claim videos attract **significantly more engagement** (views, likes, shares) than opinions  
- 🚫 Banned authors are **disproportionately associated** with claim content  
- ✅ Verified users tend to post **opinion-based content**  
- 📈 Engagement data is **heavily skewed**, highlighting the need for outlier handling in models  
- ⚠️ Detected **200+ nulls** across 7 variables, requiring thorough cleaning and imputation  

---

## 🧠 Methodology – PACE Strategy

### 📝 Plan  
- Key variables: `claim_status`, `verified_status`, `author_ban_status`, and engagement metrics  
- Tools: Python for EDA; Tableau for visual storytelling  
- Addressed missing values, skewness, and class imbalance  

### 🔍 Analyze  
- Used descriptive statistics & IQR-based outlier detection  
- Visualized distributions with boxplots and histograms  

### 🛠 Construct  
- Developed an **interactive Tableau dashboard**  
- Designed with **accessibility** and **executive readability** in mind  

### 🚀 Execute  
- Shared via Tableau Public for stakeholder review  
- Created an **executive summary** report aligned with business communication best practices  

---

## 📁 Included Files

| File Name                                              | Description                                         |
|--------------------------------------------------------|-----------------------------------------------------|
| `TikTok Project (Coursera).twbx`                       | Tableau workbook with dashboard & embedded dataset |
| `tiktok_dataset.xlsx`                                  | Cleaned dataset used for visual analysis           |
| `TikTok_EDA_Executive_Summary.docx`                    | Business-style summary using the PACE framework     |
| `Activity Exemplar_ TikTok Course 3 executive summary.pptx` | Slide-based executive presentation (Coursera format) |
| `Activity Exemplar_ TikTok Course 3 executive summary (OG).jpg` | Visual example of final deliverable               |

---

## 🛠 Tools & Technologies

- **Tableau Public** – Interactive dashboard and visual storytelling  
- **Python (pandas, seaborn)** – Exploratory data analysis  
- **Microsoft Excel** – Data cleaning & transformation  
- **Coursera** – Project developed in Course 3 of the Google Advanced Data Analytics specialization  

---

## 👤 Author

**Rohan Suresh**  
📬 GitHub: [@rohansuresh19](https://github.com/rohansuresh19)

---
