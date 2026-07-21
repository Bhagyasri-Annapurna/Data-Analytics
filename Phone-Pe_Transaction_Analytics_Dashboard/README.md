# 📱 PhonePe Transaction Analytics Dashboard | Power BI

An interactive **Power BI dashboard** built to analyze digital payment transactions inspired by the **PhonePe Pulse** dataset. This dashboard provides comprehensive insights into transaction volume, transaction value, user growth, payment success rates, service-wise performance, and customer demographics through interactive visualizations and custom tooltips.

---

## 📌 Project Overview

This dashboard is designed to help stakeholders monitor digital payment performance and understand customer transaction behavior.

The report enables users to:

- Monitor transaction volume and transaction value
- Analyze monthly transaction trends
- Track payment success rate
- Identify top users based on transaction amount
- Compare weekday vs weekend usage
- Analyze transactions across different services
- Understand age-group contribution
- Explore additional insights through interactive tooltips

---

## 📊 Dashboard Preview

![PhonePe Transaction Analytics Dashboard](Dashboard.png)

---

## 🚀 Dashboard Features

### Executive KPIs

- 💰 Total Transaction Amount
- 🔄 Total Transactions
- ✅ Success Rate
- 👥 Unique Users
- 📈 User Growth %
- 🆕 New Users
- 📊 Month-over-Month Growth

---

### Interactive Visualizations

- Transaction Amount & Transaction Count Trend
- Service-wise Transaction Amount
- Top 5 Users by Transaction Amount
- Payment Status Distribution
- Age Segment Contribution
- Weekend vs Weekday Usage

---

### Interactive Filters

- Month Slicer

---

### Advanced Features

✔ Interactive Tooltips

- **Tooltip 1**
  - Service Type-wise Transaction Amount

- **Tooltip 2**
  - Payment Status-wise Transactions

These tooltip pages provide additional insights without navigating away from the main dashboard, creating a more interactive user experience.

---

## 🛠 Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Custom Dashboard Background (Designed using Figma)

---

## 📈 Key Insights

- Processed over **300K transactions** with a total transaction value of **₹3.47 Billion**.
- Achieved an overall **96% payment success rate**.
- Loans contribute the highest transaction amount among all services.
- Weekday transactions significantly exceed weekend activity.
- The **31–45** age segment contributes the largest share of transactions.
- The dashboard highlights top users and payment status distribution to support business decision-making.

---

## 📂 Dataset

The dashboard is built using a relational dataset consisting of two tables:

### 1. All_Transactions (Fact Table)

Contains transaction-level information including:

- Transaction_ID
- User_ID
- Date
- Amount
- Payment_Status
- Service
- Service Type
- Reason

### 2. All_Users (Dimension Table)

Contains user demographic information including:

- User_ID
- Name
- Age
- Age Group
- Join_Date

The two tables are connected using the **User_ID** field, enabling transaction analysis alongside customer demographics.

---

## 📊 DAX Measures Used

Some of the key DAX measures include:

- Total Transactions
- Total Transaction Amount
- Success Rate
- Total Users
- New Users
- User Growth %
- Month-over-Month Transaction Growth
- Month-over-Month Amount Growth

---

## 🎯 Business Use Cases

This dashboard helps business teams to:

- Monitor digital payment performance
- Track customer growth
- Identify high-value services
- Improve payment success rates
- Analyze customer demographics
- Support strategic business decisions using data

---

## 📁 Repository Structure

```
PhonePe-Transaction-Analytics-Dashboard/
│
├── Dashboard.pbix
├── Dashboard.png
├── Dataset.xlsx
├── README.md
└── Assets/
    ├── Background.png
    └── Tooltip Pages
```

---

## 📸 Dashboard Highlights

- Modern FinTech-inspired UI
- Custom-designed dashboard background
- Responsive layout
- Interactive tooltips
- Advanced KPI cards
- Time-series analysis
- Professional Power BI report design

---

## 👩‍💻 Author

**Bhagyasri Annapurna**

💼 LinkedIn: https://www.linkedin.com/in/bhagyasri-annapurna-thota-953a91227/


---
