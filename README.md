📊 YouTube Channel Analytics Project
🚀 Project Overview

This project focuses on analyzing data from popular YouTube data analytics creators using the YouTube Data API v3. The goal is to collect channel statistics, video metadata, and engagement metrics, then transform them into meaningful visualizations and insights using Python, Pandas, Matplotlib, and Seaborn.

The project not only highlights how to gather data via APIs, but also demonstrates data cleaning, feature engineering, and storytelling through visual analytics.

🔧 Tech Stack & Tools

Python 🐍

YouTube Data API v3 (Google API Client)

Pandas (Data Wrangling & Analysis)

Matplotlib & Seaborn (Data Visualization)

NumPy (Numerical Computations)

📥 Data Collection

We focused on five popular YouTube creators in the data science & analytics community:

techTFQ

Alex The Analyst

Luke Barousse

Ken Jee

Tina Huang

Using the YouTube Data API, the script collected:

Channel Statistics (Subscribers, Views, Total Videos)

Video Details (Title, Publish Date, Views, Likes, Comments)

Engagement Metrics (Likes per View, Comments per View, Engagement Rate)

📊 Key Visualizations & Insights
1️⃣ Channel Comparison Dashboard

We compared Subscribers, Views, Total Videos, and Average Views per Video across all five creators.

Alex The Analyst and Ken Jee show strong engagement per video, even if their upload count is smaller.

TechTFQ dominates in total uploads, while Luke Barousse has higher views per video, showing strong audience resonance.

📷 (channel_comparison.png)

2️⃣ Top 10 Most Viewed Videos

A horizontal bar chart highlights the most successful videos (by views).

This reveals trending topics and audience preferences (e.g., SQL tutorials, career advice, Python projects).

📷 (top_videos.png)

3️⃣ Videos Published per Month

We analyzed the distribution of uploads across months.

Peaks in certain months suggest content sprints or strategic publishing before exam/job-hunting seasons.

📷 (videos_per_month.png)

4️⃣ Cumulative Views Over Time

A time series plot showing how views grow cumulatively.

Channels with consistent uploads (e.g., TechTFQ) show steady exponential growth.

📷 (views_over_time.png)

5️⃣ Engagement Analysis (Views vs Likes)

A scatter plot colored by Engagement Rate.

Shows how not every highly-viewed video has high engagement.

Some niche videos, while smaller in reach, had very strong engagement rates.

📷 (engagement_analysis.png)

6️⃣ Yearly Analysis

A dual-axis chart showing number of videos per year vs total views.

Strong insight: consistent posting = higher cumulative views.

Audience growth aligns with regular content production.

📷 (yearly_analysis.png)

7️⃣ Likes vs Comments Correlation

Scatter plot confirms a positive correlation between Likes and Comments.

This suggests that as videos get more engagement through Likes, they also drive community discussions.

📷 (likes_vs_comments.png)

📂 Outputs

The project generates:

Visual Reports (PNG charts saved locally)

CSV Files

Channel_Statistics.csv → Channel-level data

Video_Details.csv → Video-level insights

📌 Key Takeaways

Ken Jee and Luke Barousse excel in audience engagement per video.

TechTFQ dominates in volume of content and cumulative growth.

Alex The Analyst shows that consistent educational content pays off in long-term growth.

Engagement metrics reveal that quality matters more than quantity.

🌟 Why This Project Matters

This project demonstrates end-to-end data analysis:
✔️ API Data Collection
✔️ Data Wrangling & Cleaning
✔️ Exploratory Data Analysis (EDA)
✔️ Data Visualization & Storytelling
✔️ Actionable Insights for Strategy

It’s a perfect showcase of Data Analytics + Python Visualization skills that can be applied in real-world business problems, digital marketing analytics, or social media strategy optimization.

👉 Next Steps:

Expand dataset to include more YouTubers.

Perform topic modeling on video titles/descriptions.

Build a dashboard with Plotly/Dash or Power BI for interactive exploration.
