TikTok Claims vs Opinions: Tableau EDA Dashboard
Coursera Capstone Project — Google Advanced Data Analytics Specialization

🔗 Live Dashboard
👉 View on Tableau Public »

🎯 Project Overview
This project investigates patterns in TikTok video performance, focusing on the classification of videos as claims or opinions. The objective was to uncover how engagement metrics such as views, likes, and comment counts vary by content type—and what that might imply for content moderation or future machine learning models.

📌 Key Features
📦 Boxplots showing distribution for:

Video Duration

Like Count

Comment Count

View Count

📊 Claims vs Opinions comparison by:

Engagement metrics

Author verification and ban status

🎛️ Interactive Filters to explore relationships between variables

🔍 Insights & Impact
🔺 Claim videos attract significantly more engagement (views, likes, shares) than opinions.

🚫 Banned authors are disproportionately associated with claim content.

✅ Verified users are more likely to post opinion-based content.

📈 Engagement data is heavily skewed, suggesting outliers are common and need to be addressed in predictive modeling.

⚠️ Detected over 200 nulls across 7 variables—highlighting the need for robust data cleaning and imputation strategies.

🧠 Methodology (PACE Strategy)
Plan

Key variables: claim_status, verified_status, author_ban_status, and engagement metrics

Tools: Python for EDA and preprocessing; Tableau for visual storytelling

Considered missing values, skewness, and content-label imbalances

Analyze

Applied descriptive statistics and IQR-based outlier detection

Used boxplots and histograms to explore distributions and correlations

Construct

Built an interactive dashboard in Tableau Public

Visuals were designed with accessibility and executive-readability in mind

Execute

Shared the dashboard for stakeholder and peer feedback

Summary findings documented in a structured executive summary report

📁 Included Files
File	Description
TikTok Project (Coursera).twbx	Tableau workbook containing full dashboard
tiktok_dataset.xlsx	Cleaned dataset used for analysis
TikTok_EDA_Executive_Summary.docx	Business-style summary using the PACE framework

🛠 Tools & Technologies
Tableau Public – Interactive dashboard and storytelling

Python (pandas, seaborn) – Exploratory data analysis

Excel – Data transformation & cleanup

Coursera – Project conducted as part of a certified data analytics specialization

👤 Author
Rohan Suresh
📬 GitHub: @rohansuresh19
