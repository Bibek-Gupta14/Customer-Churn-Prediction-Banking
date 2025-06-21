# 🏦 Bank Customer Churn Analytics Dashboard 🚦
---

 Welcome to the interactive analytics dashboard for the **Bank Customer Churn** dataset! This project explores the behavior and characteristics of 500 bank customers to uncover what drives them to stay or leave. Dive in to discover data, insights, and visual summaries—all in one place!
---

## 📊 Dataset Overview

| Variable         | Description                                                          |
|------------------|----------------------------------------------------------------------|
| `CustomerID`     | Unique customer identifier                                           |
| `Surname`        | Customer's last name                                                 |
| `CreditScore`    | Credit score (350–850)                                               |
| `Geography`      | Country/Region (France, Spain, Germany)                              |
| `Gender`         | Male or Female                                                       |
| `Age`            | Customer age                                                         |
| `Tenure`         | Years with the bank                                                  |
| `Balance`        | Bank account balance (cleaned for inconsistencies)                   |
| `NumOfProducts`  | Number of banking products used                                      |
| `HasCrCard`      | Has a credit card? (1=Yes, 0=No)                                     |
| `IsActiveMember` | Active member? (1=Active, 0=Inactive)                                |
| `EstimatedSalary`| Estimated annual salary (missing values imputed with average)        |
| `Churn`          | Has the customer left? (1=Yes, 0=No)                                 |

---

## 🧹 Data Quality & Cleaning

- **Missing Salaries:** 3 missing values in `EstimatedSalary` were replaced with the average (₹82,076.70).
- **Inconsistent Balance:** 1 inconsistent value fixed by replacing with the average balance (₹128,388.87).

---

## 📈 Analytical Insights

### 🌍 Average Credit Score by Geography

| Country  |Avg. Credit Score |
|----------|------------------|
| France   | 592.55           |
| Spain    | 600.99           |
| Germany  | 579.69           |

> **Spain** leads in average credit score, while **Germany** trails slightly.

---

### 👩‍💼👨‍💼 Average Account Balance by Gender & Country

| Country  | Female Balance| Male Balance |
|----------|---------------|--------------|
| France   | ₹129,576.99   | ₹133,204.76  |
| Germany  | ₹140,888.28   | ₹128,591.02  |
| Spain    | ₹120,986.24   | ₹119,558.16  |

- **German women** have the highest average balances.
- **French men** slightly outpace French women.
- **Spanish gender gap** is minimal.

---

### 💳 Active Members vs. Credit Card Ownership

| Has Credit Card | Active | Non-Active |
|-----------------|--------|------------|
| No (0)          | 113    | 140        |
| Yes (1)         | 124    | 123        |

- **Credit card holders** are more likely to be active members!

---

### 📦 Churn Rate by Number of Products

| Products Used | Churned | Stayed | Churn Rate (%) |
|---------------|---------|--------|----------------|
| 1             | 69      | 56     | 55.2           |
| 2             | 74      | 61     | 54.4           |
| 3             | 65      | 53     | 55.1           |
| 4             | 64      | 58     | 52.5           |

- **More products = Slightly lower churn!** Encourage cross-selling.

---

### ⏳ Credit Score by Tenure & Churn Status

| Tenure (Years) | Stayed Avg. Score | Churned Avg. Score |
|----------------|-------------------|--------------------|
| 1              | 591.00            | 616.83             |
| 3              | 541.63            | 637.67             |
| 4              | 599.58            | 617.67             |
| ...            | ...               | ...                |

- **No clear linear pattern**—credit score’s impact on churn varies by tenure.

---

## 🧪 Research Insights

### 1️⃣ Salary vs. Churn

- **Churned Avg. Salary:** ₹83,428.09
- **Stayed Avg. Salary:** ₹80,464.52
- **Statistical Test:** _No significant difference_ (p = 0.42)

### 2️⃣ Credit Score by Geography

- **France:** 592.55
- **Germany:** 579.69
- **Spain:** 600.99
- **Statistical Test:** _No significant difference_ (p = 0.37)

---

## 🌟 Key Takeaways

- **Product engagement and credit card ownership** are associated with lower churn and higher activity.
- **Demographic differences** (gender, geography) affect balances and scores, but not churn directly.
- **No single factor** (salary, geography, credit score) predicts churn—focus on holistic customer engagement!

---

## 📝 How to Use [Interactive Dashboard (Excel)]

1. **Open the [Bank-Churn-Data.xlsx](Bank-Churn-Data.xlsx) file. Download the Excel file** and open in Microsoft Excel.
2. **Sheet: Data** – Full cleaned dataset
 -  **Sheet: Analytics** – Pivot tables for all analytical questions
 -  **Sheet: Dashboard** – Visual summaries and charts
3. **Navigate to the Dashboard sheet** for interactive charts.
4. **Filter and Slice** the data using Pivot Table controls to explore your own questions!


-------------------------------------------------🎓🎓🎓🎓🎓---------------------------------------------------

