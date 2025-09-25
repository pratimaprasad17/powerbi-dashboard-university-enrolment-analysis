# 🎓 Admissions Dashboard: Who Got In & Who Showed Up?

[Admissions Dashboard Who Got In & Who Showed Up.pdf](./Admissions%20Dashboard%20Who%20Got%20In%20%26%20Who%20Showed%20Up.pdf)
<img width="1611" height="913" alt="image" src="https://github.com/user-attachments/assets/cff85dcc-d97c-433d-8da8-9a4ff29a454e" />



> A Power BI dashboard that reveals the story behind U.S. college admissions, enrollments, tuition costs, and demographic trends — powered by IPEDS Fall 2023–24 data.

---

## 📌 Project Overview

This dashboard explores **institutional admissions and enrollment** and visualizes **trends in U.S. higher education based on institutional data**, focusing on:

- Admission rates by gender
- Enrollments by residency and ethnicity
- Tuition & cost of attendance by student type
- Revenue vs expenditure breakdowns for public institutions
- Distance education adoption
- Demographic profiles of enrolled students

The dashboard aims to provide stakeholders (university administrators, policy analysts, and education researchers) with insights into:

- Who is getting admitted?
- Who is actually enrolling?
- What are the trends by gender, residency, race/ethnicity, tuition cost, and delivery modes (online vs. on-campus)?

The story behind the dashboard revolves around tracking the **pipeline from application to enrollment**, with a focus on **equity, access, affordability**, and **demographic breakdowns**.

---
## 🚀 Live Dashboard

> [🔗 View Dashboard on Power BI (Click here)](https://app.powerbi.com/reportEmbed?reportId=bf6b5141-6599-4b78-9ada-0ebb7d608c33&autoAuth=true&ctid=41f88ecb-ca63-404d-97dd-ab0a169fd138)

---

## 🧩 Data Source

This dashboard is built using institutional characteristics data from the **Integrated Postsecondary Education Data System (IPEDS)**, Fall 2023–24 Provisional Release.

- 📁 Dataset: [institution-profile-dataset.xlsx](./institution-profile-dataset.xlsx)
- 📊 Dashboard File: [ASU Admissions Dashboard.pbix](./ASU%20Admissions%20Dashboard.pbix)
- 📍 Source: U.S. Department of Education – IPEDS Fall 2023–24 Provisional Release
---

## 🛠️ Tools Used

- **Power BI Desktop** – Data modeling, cleaning, and interactive visual design
- **Microsoft Excel** – Pre-cleaning and schema inspection
- **Power Query Editor** – Transformations, filters, DAX measures
---

## 🧹 Data Cleaning & Transformation

- Removed aggregate rows and irrelevant summary footers
- Transformed numerical columns to proper types
- Converted percentage columns to numeric ratios
- Created calculated columns for:
  - **Net enrollment rates by gender**
  - **Average tuition & fees breakdown**
  - **In-state vs Out-of-state comparisons**
- Applied conditional formatting and slicers for dynamic interactivity

---

## 🛠️ Features & Visuals

| Feature                             | Description                                                                 |
|-------------------------------------|-----------------------------------------------------------------------------|
| 🎓 Admissions Breakdown             | Applicants vs Admissions vs Enrollments, by gender                         |
| 🌎 Residency Distribution           | In-state vs Out-of-state vs International students                         |
| 📈 Tuition & Net Price Trends       | Breakdown by income level, residence, and degree type                      |
| 🧮 Cost of Attendance Visualization | On-campus vs Off-campus (with/without family) comparisons                  |
| 🌐 Distance Learning Adoption       | Percent of students enrolled in remote/online education                    |
| 💸 Revenue vs Expense Breakdown     | Source of core revenues and allocation of institutional expenses           |
| 📊 Demographics by Ethnicity & Age  | Race/ethnicity and age-wise distribution across undergraduate & graduate   |

---
## 🔍 Insights & Takeaways

### 1. **Gender Parity in Admissions**
- Admissions and enrollment are nearly 50/50 between men and women.
- Slightly higher enrollment percentages for women post-admission.

### 2. **Rising Costs & Varying Net Price**
- Published tuition for graduate students is **~$32,000 (out-of-state)** vs **~$12,000 (in-state)**.
- Net price after aid is **highly dependent on income**, with those under $30,000 seeing the steepest aid impact.

### 3. **In-State Dominance but Rising Out-of-State Enrollments**
- In-state students dominate, but out-of-state enrollment is a growing revenue source.

### 4. **Distance Education Shift**
- Around 40%+ students are enrolled in some form of online learning — showing a permanent shift in delivery mode post-pandemic.

### 5. **Revenue vs Expense Gaps**
- Tuition is the largest revenue source (~43%), followed by government grants and state appropriations.
- Instruction and institutional support form the bulk of expenditures.

---
## ⚠️ Limitations

- Dataset includes **provisional IPEDS data**, which may be revised in future releases.
- No longitudinal time-series to show multi-year trends within the same visual.
- Dashboards reflect **aggregated** institutional data — individual program-level variations are not shown.

---

## 📁 Repository Structure

```bash
📦 admissions-dashboard-powerbi/
├── 📊 ASU Admissions Dashboard.pbix                            # Power BI project
├── 📄 Admissions Dashboard Who Got In & Who Showed Up.pdf      # Static dashboard export
├── 📈 institution-profile-dataset.xlsx                         # Excel source data
└── 📝 README.md                                                # Project story, description & dashboard link
```
--- 
## 🛠️  Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/pratimaprasad17/powerbi-dashboard-university-enrolment-analysis.git
    cd powerbi-dashboard-university-enrolment-analysis
    ```

2.  Ensure you have Power BI Desktop installed.

🌟 You are all set!

## 🧐 Dependencies

*   [Power BI Desktop](https://powerbi.microsoft.com/desktop/): Required to open and interact with the dashboard.
*   [Excel dataset](./institution-profile-dataset.xlsx): Excel file containing the data source.

## 🖥️ How to Use

1. Download the [ASU Admissions Dashboard.pbix](./ASU%20Admissions%20Dashboard.pbix) file and the [Excel dataset](./institution-profile-dataset.xlsx).
2.  Open the .pbix file in **Power BI Desktop**.
3.  Refresh the data source if prompted to ensure the dashboard is up-to-date.
4.  Explore the various visualizations and reports to gain insights into university enrollment analysis.
5.  Use this dashboard to present institutional findings, support grant applications, or inform policy briefs.

## 🍰 Contributing

Contributions are welcome! Here's how you can contribute:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive messages.
4.  Submit a pull request.

## 📢 Author

👩‍💼 Pratima Prasad  
🎓 MS in Computer Science'25 | Arizona State University  
💼 Data Analyst | Business Intelligence | Microsoft Power BI Certified  
👔 [LinkedIn](https://www.linkedin.com/in/pratima-prasad/) | 🌐 [Portfolio](https://pratimaprasad17.github.io/portfolio/) | 📫 [Email](pratima.p1709@gmail.com)

#### ⭐️ If you found this project useful, please consider starring the repo!
```
