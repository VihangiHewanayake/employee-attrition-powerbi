# 📊 Employee Stability & Attrition Analysis
### Power BI Dashboard | Group 08

---

## 📌 Project Overview

This project analyzes employee attrition patterns using the IBM HR Analytics dataset to help organizations understand **who is leaving, why they leave, and which employee groups are most at risk**.

The interactive Power BI dashboard supports strategic HR decision-making by identifying key attrition drivers across demographic, job-related, and workplace factors.

---

## ❗ Problem Statement

Organizations face serious consequences from employee attrition including:
- Talent loss and knowledge gaps
- Productivity decline
- Increased hiring and onboarding costs

Management often lacks visibility into attrition trends — this dashboard addresses that gap.

---

## 📁 Project Structure

```
employee-attrition-powerbi/
│
├── images/
│   ├── dashboard_overview.png
│   ├── dashboard_attrition_drivers.png
│   └── dashboard_employee_segmentation.png
│
├── updated.pbix
├── Presentation_Power_BI.pdf
└── README.md
```

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `updated.pbix` | Power BI dashboard file (open with Power BI Desktop) |
| `Presentation_Power_BI.pdf` | Project presentation slides |
| `README.md` | Project documentation |

---

## 🗄️ Dataset

| Attribute | Details |
|-----------|---------|
| **Dataset** | IBM HR Analytics – Employee Attrition |
| **Source** | [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) |
| **Domain** | Human Resource Management |
| **Total Records** | 1,470 employees |
| **Total Features** | 35 variables |
| **Missing Values** | None |

---

## 🔧 Data Preparation

Calculated measure columns created to support analysis:
- Total Employees
- Active Employees
- Attrition Count
- Attrition Rate (%)
- Average Monthly Income
- Average Job Satisfaction

Categorical variables were transformed for better interpretation:

| Variable | Encoding |
|----------|----------|
| **Job Satisfaction** | 1=Low, 2=Medium, 3=High, 4=Very High |
| **Work-Life Balance** | 1=Bad, 2=Good, 3=Better, 4=Best |
| **Education** | 1=Below College, 2=College, 3=Bachelor, 4=Master, 5=Doctor |

---

## 🔍 Key Insights

1. **Attrition peaks in early years of employment** — Onboarding and early-career support are critical retention levers.

2. **R&D and Sales are the most vulnerable departments** — These departments have the highest attrition rates and should be priority areas for HR intervention.

3. **Sales Executives and Research Scientists are high-risk roles** — High headcounts combined with elevated attrition amplify business impact.

4. **Low job satisfaction strongly drives attrition** — Employees with low satisfaction leave at significantly higher rates, making satisfaction a key retention factor.

5. **Poor work–life balance and overtime increase attrition** — Workload pressure and burnout push employees to leave.

6. **Younger, lower-income employees are most likely to leave** — Pay and growth expectations are major drivers for early-career employees.

---

## 📸 Dashboard Screenshots

### 🔹 Page 1 — Overview
![Overview Dashboard](images/dashboard_overview.png)
> Key KPIs: Total Employees (1,470), Attrition Count (237), Attrition Rate (16.1%), Average Monthly Income ($6.50K). Breakdowns by Department, Age, Marital Status, and Education Level.

---

### 🔹 Page 2 — Attrition Drivers
![Attrition Drivers Dashboard](images/dashboard_attrition_drivers.png)
> Analysis of attrition by Job Satisfaction, Work-Life Balance, Overtime, Years at Company, and Monthly Income.

---

### 🔹 Page 3 — Employee Segmentation
![Employee Segmentation Dashboard](images/dashboard_employee_segmentation.png)
> Attrition breakdown by Job Role, Years at Company, Job Satisfaction per Role, and Years in Current Role.

---

## 🛠️ Tools & Technologies

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

---

## 🚀 How to View the Dashboard

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `updated.pbix` in Power BI Desktop
4. Explore the interactive dashboard

---

## 👥 Group Members — Group 08

| Student ID | Name |
|------------|------|
| s17002 | Wijesundara B. L. D. T. S. |
| s16938 | Dharmasena J. B. A. A. Y. |
| s16770 | Sathsarani H. N. V. K. |
| s16714 | Pattidora S. K. |

---

## 📄 License

This project is for academic purposes only.
