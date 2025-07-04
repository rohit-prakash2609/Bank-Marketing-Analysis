# 📊 Bank Marketing Analysis - Power BI Project

## 🔍 Project Overview  
In the highly competitive BFSI (Banking, Financial Services & Insurance) landscape, understanding customer responsiveness to term-deposit campaigns is key to boosting marketing ROI and customer acquisition. This Power BI project analyzes a real-world dataset from a Portuguese bank's telemarketing campaign to:

- Evaluate campaign effectiveness  
- Identify high-conversion customer segments  
- Forecast future term-deposit subscriptions  
- Optimize call strategies for better resource allocation  

---

## 🧾 Dataset Description  
**Source**: UCI Machine Learning Repository (Bank Marketing Dataset)  
**Records**: 4,521  
**Fields**: 17 attributes including customer demographics, contact details, past interactions, and campaign outcomes  

**Key Features**:  
`age`, `job`, `marital`, `education`, `default`, `balance`, `housing`, `loan`  
`contact`, `day`, `month`, `duration`, `campaign`, `pdays`, `previous`, `poutcome`, `y` (target)

---

## 🎯 Business Problem  
The marketing team of a mid-sized European bank aims to answer:

- Which contact channels and timings drive the most subscriptions?  
- What customer profiles are most likely to subscribe to term deposits?  
- How can call strategies be optimized for future campaigns?  
- Can we forecast term-deposit uptake trends?

---

## 🧩 Tasks & Deliverables

| Task | Deliverable |
|------|-------------|
| **1. Data Profiling** | Summary of each column (data type, top values, % nulls), with a narrative on anomalies |
| **2. Data Cleaning** | Log of transformations, missing value handling, and outlier treatment |
| **3. Date Handling** | Generated `ContactDate`, linked to Date Dimension with time-intelligence hierarchy |
| **4. DAX Calculations** | Measures like `TotalCalls`, `SuccessCount`, `SubscriptionRate`, `AvgBalance`, etc. |
| **5. Customer Profiling** | Conversion rates by job, education, and other demographic splits |
| **6. Campaign Dashboard** | Multi-page Power BI report with KPIs, visuals, and key takeaways |
| **7. Time Trends & Forecasting** | Trend charts with 3-month forecasts and seasonality highlights |
| **8. Funnel Analysis** | Four-stage funnel with drop-off rates and insights |
| **9. Segmentation** | 3–5 clusters by age, balance, and call duration; labeled and prioritized |
| **10. Insights & Recommendations** | 1-page summary with actionable strategies and suggested KPIs |

---

## 📈 Sample Visualizations  

- 📌 **KPI Cards**: `TotalCalls`, `SubscriptionRate`, `AvgDuration`  
- 🧠 **Demographics**: Heatmaps by age and balance buckets  
- 📆 **Trends**: Monthly subscriptions with forecast bands  
- 🔄 **Funnel Chart**: Prospect drop-off across campaign stages  
- 🔍 **Segment Analysis**: Cluster visuals with summaries  

---

## 🧠 Key Insights (Example Snippets)  

- Customers aged **30–45** with a balance > EUR 1,000 and no existing loans show the highest subscription rate.  
- **May and August** witnessed peak conversions—suggesting optimal windows for future campaigns.  
- Conversion rates drop **drastically after the third contact attempt**, indicating diminishing returns.  

---

## 📝 Recommendations  

- 📅 Target campaigns during high-conversion months (e.g., May, August)  
- 👥 Prioritize high-balance, employed individuals with no prior defaults  
- 📞 Limit repeat calls beyond 3 attempts to save resources  
- 📊 Monitor KPIs like `SubscriptionRate`, `Call Duration`, and `Channel Efficiency`  

---

## 🧪 Tech Stack  

- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Power Query (M Language)  
- Excel / CSV for raw data  

---

## 📢 Presentation  

A live demo will walk through:

- Dashboard navigation and filters  
- DAX logic and data model  
- Business insights and recommendations  

---

## 🏁 Final Notes  

This project showcases data storytelling through interactive dashboards that help drive informed decisions in financial marketing. For any suggestions, feel free to raise an issue or contribute.

---

## ✍️ Author  
**Rohit Prakash**  
Data Analytics Enthusiast | Retail Professional Transitioning to Data Analyst  
📧 rohit4pro@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/rohit-prakash-3980867a)

![image](https://github.com/user-attachments/assets/f56dffb6-5a17-470b-bf1c-3356e51a0b5e)
