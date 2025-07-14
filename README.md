# Cohort Analysis Project 📈

This project showcases a comprehensive cohort analysis to understand customer behavior and retention over time. The goal was to analyze retention and churn across different customer acquisition groups, identify key trends, and provide actionable recommendations for improving customer longevity.

## Project Overview 📊

The analysis utilizes customer subscription data to define cohorts based on their `subscription_start` date. Through data preparation and the calculation of retention metrics within **Google Sheets**, this project uncovers customer engagement patterns and pinpoints critical churn periods for targeted retention strategies.

---



## Key Findings & Insights 💡

The cohort analysis revealed several critical patterns in customer behavior:

* **Overall Churn Trend:** Across all cohorts, customer churn increased week over week. Average retention dropped from 94.49% (W_0) to 74.23% (W_6), indicating significant customer loss within six weeks. Churn rates conversely rose from 5.51% to 25.77%.
* **Early Retention Cohorts:** Cohorts starting 11/1/2020 and 11/8/2020 presented lower churn from W_0 to W_3, but churn increased from W_4. This suggests applying retention strategies from W_4 for these groups.
*  **Recent Cohort Vulnerabilities:** More recent cohorts (starting 11/22/2020 to 12/6/2020) exhibited higher churn in their first weeks, emphasizing the critical importance of initial customer experience.
* **Individual Cohort Nuances:** Individual cohorts displayed unique retention/churn profiles, highlighting the need for granular analysis to pinpoint specific influencing factors.

---

## Actionable Recommendations ✅

* **Investigate High-Churn Cohorts:** Analyze differences in onboarding, marketing, product features, customer support, or external factors during their acquisition period.
* **Analyze Best Practices from Low-Churn Cohorts:** Examine successful onboarding, initial product engagement, and communication strategies. Replicate or scale these across new cohorts.
* **Segmented Analysis:** Further segment cohorts (e.g., by acquisition channel, demographic, initial product usage) to reveal segments more prone to churn or better retained, allowing targeted interventions.
*  **Develop a "Red Flag" System:** Identify early behaviors predictive of churn. Implement a system to flag at-risk customers for targeted interventions (e.g., personalized outreach, offers, assistance).

---

## Technologies Used 💻

* **Google Sheets**: Used for all data manipulation, calculations, retention matrix creation, and dashboard visualization. 📊
* **Google Gemini**: Utilized as an AI assistant during the data preparation and calculation formulation process. 🤖

---

## Repository Structure 📂

* `data/cohort_data.csv`: The cleaned dataset used for this analysis.
* [Google Sheets File with Insights](https://docs.google.com/spreadsheets/d/1zLM6Rs6ivgknKJu5-tor10ElLz3pjz_5dyc6FOGdl6s/edit?gid=1005723545#gid=1005723545)

---
