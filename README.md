FOOD - User Insights Analysis
Overview
FOOD is a web and mobile service designed to help travelers discover personalized restaurant recommendations. This project analyzes user behavior to provide data-driven insights that can improve user retention, optimize marketing strategies, and enhance re-engagement efforts.

This analysis was initially conducted as part of a hiring assignment but has been expanded into a standalone data project.

Objectives
This project explores three key areas:

1️⃣ User Retention Analysis
Calculate user retention rates and identify trends.
Analyze cohort data to pinpoint periods of high and low retention.
Provide recommendations for improving user engagement and retention strategies.

2️⃣ Marketing Channel Performance
Determine the most effective acquisition channels based on average revenue per user (ARPU).
Compare the impact of channels such as Google Ads, Facebook Ads, Referrals, Organic Search, and Email Campaigns.
Offer marketing recommendations to optimize budget allocation and improve high-value user acquisition.

3️⃣ Re-Engagement Strategy
Identify the optimal time window to re-engage first-time users and encourage a second transaction.
Analyze user return behavior across different time frames (0-30 days, 30-90 days, 90+ days).
Suggest personalized re-engagement strategies based on platform usage and user preferences.
Dataset
The dataset includes the following key columns:

user_id – Unique identifier for each user.
transaction_date – Date of each transaction.
revenue – Revenue generated from the transaction.
platform – Platform used (web or app).
acquisition_channel – Channel through which the user was first acquired.

Key Insights & Recommendations
1️⃣ User Retention Trends
High early retention (90%+) was observed in earlier cohorts, but retention steadily declined in later months.
Seasonality effects were identified, affecting user engagement during holiday periods.
Later cohorts experienced lower retention, possibly due to onboarding inefficiencies or engagement gaps.
🔹 Recommendations:
✔ Improve onboarding with clear value propositions.
✔ Re-engage users within 7 days using personalized incentives.
✔ Implement segmented retention campaigns based on user preferences.

2️⃣ Marketing Channel Performance
Google Ads drove the highest ARPU, making it the most effective channel.
Referrals and Facebook Ads performed well and contributed significantly to high-value user acquisition.
Organic Search and Email Campaigns showed lower revenue impact but could still be leveraged cost-effectively.
🔹 Recommendations:
✔ Increase investment in Google Ads and optimize targeting.
✔ Enhance referral programs with discounts and rewards.
✔ Improve Facebook Ads strategies by experimenting with creatives and retargeting.

3️⃣ Re-Engagement Strategy
Most users return within 18 days, making it the optimal time to re-engage them.
Users beyond 90 days become significantly harder to bring back.
App users engage more frequently than web users due to push notifications.
🔹 Recommendations:
✔ Within 30 days: Send personalized thank-you messages and time-limited offers.
✔ 30-90 days: Use retargeting, product recommendations, and exclusive discounts.
✔ 90+ days: Launch comeback campaigns with special incentives.

Technologies Used
Python (Pandas, NumPy) – Data processing & analysis
Matplotlib, Seaborn – Data visualization
Jupyter Notebook – Interactive analysis environment
