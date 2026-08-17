GitHub ke liye **professional + ATS/resume-friendly README description** ye rahegi. Screenshot ko repo mein `assets/phonepe-dashboard.png` naam se upload karke use kar sakte ho.

# 📊 PhonePe Payment Insights Dashboard

![PhonePe Payment Insights Dashboard](assets/phonepe-dashboard.png)

## PhonePe Preiview
<img width="1916" height="982" alt="Screenshot 2026-08-17 234349" src="https://github.com/user-attachments/assets/13a17c8e-f980-4c3b-bacf-b5dc40946889" />


## 📌 Project Overview

An interactive **PhonePe Payment Insights Dashboard** built using **Microsoft Power BI** to analyze transaction performance, payment success rates, user behavior, and service-wise transaction trends.

The dashboard transforms transaction data into meaningful business insights through interactive KPIs, trend analysis, segmentation, and visual analytics.

## 🚀 Key Features

* 📈 **Total Transactions** — Monitor overall transaction volume.
* 💰 **Total Transaction Value** — Track transaction value and financial performance.
* 👥 **Unique Users** — Analyze the number of active users.
* ✅ **Successful Rate** — Monitor successful transaction performance.
* 📊 **MOM Growth Analysis** — Compare current and previous month performance.
* 🕐 **Transactions Over Time** — Identify monthly transaction trends.
* 👤 **Top 5 Users** — Analyze users based on transaction value.
* 💳 **Service-wise Analysis** — Compare transaction value across services.
* 🎯 **Age Segment Contribution** — Understand transaction contribution by age group.
* 📅 **Weekday vs Weekend Analysis** — Compare user activity patterns.
* 🔍 **Interactive Filters** — Analyze data dynamically using Month and Payment Status filters.

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Interactive Data Visualization**

## 📐 DAX & Analytics

The project uses DAX measures to calculate important KPIs such as:

* Total Transactions
* Total Transaction Value
* Unique Users
* Successful Rate
* Previous Month Transaction Value
* Month-over-Month (MOM) Growth %

Example:

```DAX
Trans Value MOM% =
DIVIDE(
    [Total Transaction Value] - [Trans Value PM],
    [Trans Value PM],
    0
)
```

## 💡 Key Insights

The dashboard helps identify:

* Monthly transaction growth and fluctuations
* Overall payment success performance
* High-value users
* High-performing payment services
* Age-group contribution to transaction value
* Weekday and weekend transaction behavior

## 🎯 Project Objective

The primary objective of this project is to demonstrate how **Power BI, DAX, and data visualization** can be used to convert transaction data into an interactive business intelligence dashboard and support data-driven decision-making.

## 📂 Project Structure

```text
PhonePe-Payment-Insights-Dashboard/
│
├── assets/
│   └── phonepe-dashboard.png
│
├── PhonePe-Payment-Insights.pbix
│
└── README.md
```

## 👨‍💻 Skills Demonstrated

**Power BI | DAX | Power Query | Data Cleaning | Data Modeling | KPI Development | Data Visualization | Business Intelligence | Analytical Thinking**

---

⭐ If you find this project useful, feel free to star the repository!
