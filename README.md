
# 🇦🇺 Australian Population Demographics Analysis (1996–2016)

### 📊 Power BI Dashboard Project | Public Sector Focus

---

## 📘 Project Overview

This repository contains an interactive **Power BI report** that analyzes the **Australian Estimated Resident Population** across five census years: **1996, 2001, 2006, 2011, and 2016**.

Developed as part of a Business Analytics course, the project focuses on uncovering key **demographic trends** and crafting **actionable insights** for public sector strategy, particularly centered around **country of birth** data over two decades.

---

## 📂 Data Source

**Australian Bureau of Statistics (ABS)** –

> Dataset: *Estimated Resident Population by Country of Birth, Sex, Age and State/Territory*

Key dataset dimensions:

* 🗺️ **States/Territories**: NSW, VIC, QLD, WA, SA, TAS, NT, ACT
* 👥 **Age Groups**: 16 x 5-year age cohorts (0–4 to 85+)
* 🚻 **Sex**: Male and Female
* 🌍 **Country of Birth (COB)**: Australia + 9 selected countries/regions
* 📅 **Years**: Census years – 1996, 2001, 2006, 2011, 2016

> ⚠️ **Note**: Raw data (`AUS_COB_ABS.csv`) is not included due to size restrictions. It is available [directly from ABS](https://www.abs.gov.au).

---

## 🗂️ Project Structure

```
├── PowerBI_Report/
│   └── Client Report.pbix              # Fully interactive Power BI dashboard
│
├── Documentation/
│   └── Client_Report_Final.pdf        # Summary report (static, key visuals & recommendations)
│
└── README.md                          # Project overview and instructions
```

---

## 📈 Dashboards & Analysis

The Power BI report features **three interactive dashboards**, each tailored to specific analytic goals:

### 1. 🔍 **Overall Population Trends**
<img width="1274" height="726" alt="Screenshot 2025-07-30 at 2 08 59 pm" src="https://github.com/user-attachments/assets/f27a8b6e-1d82-45f2-855f-e0a4c7a75340" />

* National population growth (1996–2016)
* Distribution by state/territory
* Sex and broad age group breakdowns

### 2. 🌐 **Country of Birth (COB) Insights**
<img width="1273" height="729" alt="Screenshot 2025-07-30 at 2 10 10 pm" src="https://github.com/user-attachments/assets/d4dd7617-80df-4095-87a1-7c20bd2a3193" />


* Focus on Australia + 9 selected overseas countries
* Trends by age, sex, and geographic distribution
* Comparison across census years

### 3. 📌 **Demographic Deep Dives**
<img width="1277" height="728" alt="Screenshot 2025-07-30 at 2 09 36 pm" src="https://github.com/user-attachments/assets/99c2eab1-b2a7-4b79-8c35-9dedbfe430d9" />

* Key trends and patterns:

  * Aging populations within COB groups
  * Gender distribution shifts
  * Emerging migrant concentrations by region

> 🛠️ **Power BI techniques used**: Data modeling (DAX), Power Query (ETL), interactive filters, dynamic visuals (bar, line, maps, treemaps)

---

## 💻 How to Use This Report

### ✅ Prerequisite

* Install [**Microsoft Power BI Desktop**](https://powerbi.microsoft.com/desktop/)

### 📥 Get the Repository

* **Option 1 – Clone with Git:**

  ```bash
  git clone https://github.com/YourGitHubUsername/Australian_Demographics_PowerBI_Report.git
  ```

* **Option 2 – Download ZIP:**

  * Click the green **Code** button and select **Download ZIP**

### 🚀 Open the Report

1. Navigate to `PowerBI_Report/`
2. Open `Client Report.pbix` with Power BI Desktop
3. Explore the dashboards using interactive filters and slicers

---

## 🧰 Technologies Used

| Tool                 | Purpose                                |
| -------------------- | -------------------------------------- |
| **Power BI Desktop** | Data modeling, ETL, dashboards         |
| ** Excel   | Preliminary cleaning/lookups |

---

## 🧾 License

This project is licensed under the **MIT License**.
See the [LICENSE](./LICENSE) file for details.

---

## 👤 Author

**Hassan Mohammad**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin\&style=flat-square)](https://www.linkedin.com/in/hassan1207/)
📧 [hassan\_md@live.com](mailto:hassan_md@live.com)

---
