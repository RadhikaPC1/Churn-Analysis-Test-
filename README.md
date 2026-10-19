# 📉 PhoneNew Customer Churn Analysis Dashboard

A customer churn analysis for **PhoneNew**, a telecom services company, presented through an interactive dashboard. The project identifies *who* is leaving, *why they are likely leaving*, and *what the business can do about it*, and summarises the results as findings and recommendations for leadership.

---

## 🎯 Project Overview

Customer churn directly reduces recurring revenue and increases acquisition costs. This project analyses PhoneNew's customer base to:

- Measure the overall churn rate
- Find the customer segments with the highest churn (by internet service, contract type, payment method and household profile)
- Turn those patterns into practical retention actions
- Track progress against support and payment KPIs

---

## ❓ Business Problem

> **Which customers are leaving PhoneNew, what do they have in common, and how can the company reduce churn?**

---

## 📈 Key Metrics

| Metric | Value |
|---|---|
| Total Customers | **7,043** |
| Churned Customers | **1,869** |
| Retained Customers | **5,174** |
| Overall Churn Rate | **26.54%** |

---

## 🔍 Key Findings

1. **High overall churn:** 26.54% of customers have left (1,869 out of 7,043).
2. **Fiber optic is the biggest problem area:** Fiber optic customers have the highest churn rate of any internet service, at **41.89%**.
3. **Contract type matters:** Month-to-month contracts show significantly higher churn than 1-year and 2-year contracts.
4. **Payment method matters:** Customers paying by **electronic check** have the highest churn rate.
5. **Household factor:** **36%** of churned customers have a partner, which points to a possible risk factor in this group.

---

## 💡 Recommendations

| # | Recommendation | Addresses |
|---|---|---|
| 1 | Run targeted loyalty programs and service improvements for fiber optic customers | Fiber optic churn |
| 2 | Offer incentives to move customers onto 1–2 year contracts | Month-to-month churn |
| 3 | Investigate the causes of churn among electronic check users and promote alternative payment methods | Payment method churn |
| 4 | Develop retention strategies specifically for customers with partners | Household segment |
| 5 | Strengthen tech support for fiber optic customers | Support quality |
| 6 | Convert more customers to automatic payments | Payment reliability |

---

## 🎯 KPI Targets

| KPI | Target |
|---|---|
| Support tickets per fiber optic customer | **0.5 tickets per customer** |
| Customers on automatic payments | **5% yearly increase** |

---

## 🗂 Dataset

The analysis covers **7,043 customers**. The fields below are the ones typically used in this kind of churn analysis; update the table to match your actual source file.

| Column | Description |
|---|---|
| Customer ID | Unique customer identifier |
| Partner | Whether the customer has a partner |
| Internet Service | DSL / Fiber optic / None |
| Contract | Month-to-month / One year / Two year |
| Payment Method | Electronic check, mailed check, bank transfer, credit card |
| Tech Support | Whether the customer has tech support |
| Churn | Yes / No |

---

## 🛠 Tools & Technologies

- **Dashboard tool:** *(add yours, e.g. Power BI / Tableau / Excel)*
- **Data preparation:** *(e.g. Power Query / SQL / Python)*
- **Source data:** CSV / Excel

---

## 🚀 How to Use

1. **Clone** the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open the dashboard file in your BI tool.
3. Update the data source path if prompted.
4. Use the filters and visuals to explore churn by internet service, contract, payment method and more.
5. Read the findings and recommendations above (or the summary email in the repo) for the business conclusions.

---

## 🔮 Future Improvements

- Build a **predictive churn model** (e.g. logistic regression or random forest) to flag at-risk customers
- Add **customer lifetime value** to prioritise high-value retention
- Add monthly **churn trend** tracking
- Run **A/B tests** on retention offers

---


---

⭐ If you found this project useful, consider giving it a star!
