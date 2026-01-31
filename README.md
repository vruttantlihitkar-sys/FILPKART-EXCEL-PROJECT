# 📊 Customer Service Analytics – Flipkart (Excel Project)

## 📌 Project Overview
Flipkart is one of India’s leading e-commerce platforms and relies heavily on customer service to maintain customer satisfaction and retention. In this project, customer call data was analyzed using **Microsoft Excel** to understand how customer service factors such as response time, sentiment, call duration, channel, and region impact **Customer Satisfaction Score (CSAT)** and, indirectly, customer retention.

The project follows an end-to-end analytics workflow: **data preparation → exploratory data analysis → dashboarding → insights & recommendations**.

---

## 🎯 Business Objective
- Identify customer service issues contributing to lower customer satisfaction
- Understand key drivers affecting CSAT
- Provide data-backed recommendations to improve customer experience and retention

---

## 🧾 Dataset Description
The dataset contains **30,000 customer service call records** with the following key attributes:

- Customer demographics (gender, location)
- Call details (timestamp, duration, channel, reason)
- Operational metrics (response time, call center)
- Customer feedback (sentiment, CSAT score)

---

## 🛠️ Tools & Technologies
- **Microsoft Excel**
  - Power Query (basic cleaning)
  - Pivot Tables
  - Pivot Charts
  - Slicers
  - Excel Dashboards

---

## 🧹 Data Preparation Steps
The following data preparation steps were performed to ensure accuracy and consistency:

1. Cleaned missing City and State values and replaced `#N/A` with **“Unknown”**
2. Standardized Gender values for consistency
3. Converted call timestamps into proper date format
4. Handled missing CSAT values by excluding them from average calculations
5. Categorized customer sentiment into ordered levels (Very Negative → Very Positive)
6. Converted sentiment into numeric scores for analysis
7. Categorized response time into SLA-based groups (Good, Average, Poor)
8. Created call duration buckets (Short, Medium, Long)
9. Removed duplicate and inconsistent records
10. Created derived columns to support pivot analysis and dashboards

---

## 📐 Metrics & KPIs Defined
- Average CSAT Score
- Response Time (SLA compliance)
- Average Call Duration
- Sentiment Distribution
- Call Volume
- CSAT by Channel
- CSAT by Call Center
- CSAT by Region (State/City)

---

## 🧪 Hypotheses Tested
1. Higher response time leads to lower CSAT
2. Negative sentiment customers have lower CSAT
3. Longer call durations negatively impact customer satisfaction
4. Customer satisfaction varies across call centers and channels
5. Certain regions consistently underperform in CSAT

---

## 📊 Exploratory Data Analysis (EDA)
EDA was performed using **pivot tables and charts** to uncover patterns and trends, including:

- CSAT vs Sentiment
- CSAT vs Response Time (SLA)
- CSAT vs Call Duration
- CSAT by Channel
- CSAT by Call Center
- CSAT by State (Top 10)
- Customer distribution across India
- Call volume trends over time
- Reason-wise call distribution

---

## 📈 Dashboard
An **interactive Excel dashboard** was built to summarize insights, featuring:

- KPI Cards (Total Calls, Avg CSAT, Avg Call Duration, % Poor SLA)
- CSAT vs Sentiment
- CSAT vs Response Time
- CSAT by Channel and Call Center
- Call Volume by Reason
- Time-series trend of customer calls
- Slicers for Date, Channel, Sentiment, and Response Time

---

## 🔍 Key Insights
- Calls handled **outside SLA** consistently result in lower CSAT
- **Negative and neutral sentiment** customers form the majority and lower overall satisfaction
- **Billing-related issues** account for nearly 70% of customer calls
- Certain call centers and regions consistently underperform
- Medium-duration calls tend to have slightly better satisfaction than very short or long calls

---

## ✅ Recommendations
- Reduce SLA breaches by improving response time efficiency
- Provide targeted training for handling negative sentiment customers
- Improve first-call resolution for billing-related issues
- Strengthen customer service capacity in high-volume regions
- Optimize chatbot workflows to improve CSAT

---

## 📁 Repository Structure
