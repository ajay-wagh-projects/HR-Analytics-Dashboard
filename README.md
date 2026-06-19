# HR Analytics Dashboard | Power BI

An interactive Power BI dashboard that analyzes employee attrition trends, helping HR teams identify the key drivers behind employee turnover and make data-informed retention decisions.

![HR Analytics Dashboard](dashboard_screenshot.png)

## 📊 Overview

This dashboard provides a 360° view of workforce attrition across departments, salary bands, job roles, age groups, and experience levels. It's built to help HR and business leaders quickly answer questions like:

- Which departments are losing the most employees?
- Does attrition correlate with salary, satisfaction, or experience?
- Which job roles and demographics are most at risk?
- How does attrition trend across tenure?

## 🔑 Key Metrics (KPIs)

| Metric | Value |
|---|---|
| Total Employees | 1.403K |
| Active Employees | 1.176K |
| Attrition Count | 227 |
| Attrition Rate | 16.2% |
| Average Age | 36.97 |
| Average Experience | 7.05 years |

## 📈 Dashboard Visuals

- **Attrition by Department** — Donut chart breaking down attrition share across Administration, Sales, Operations, IT, Marketing, HR, and Finance
- **Attrition by Salary Slab** — Stacked bar chart comparing attrition (Yes/No) across salary bands (0–3 LPA to 10+ LPA)
- **Attrition by Job Role & Satisfaction** — Matrix view cross-referencing job roles against satisfaction levels (1–4)
- **Age Group Distribution** — Column chart of employee count by age bracket
- **Attrition by Gender** — Pie chart split of attrition by Male/Female
- **Attrition Trends by Experience** — Area chart showing attrition count plotted against years of experience
- **Department Filter Panel** — Slicer buttons for drilling into a specific department
- **Age Group Filter** — Slicer buttons across the top for filtering by age band

## 🧠 Key Insights

- Administration (37%) and Sales (22%) account for the largest share of attrition by department
- Employees in the 6–10 LPA salary slab show the highest attrition count (71)
- Laboratory Technician and Sales Executive roles report the highest attrition volumes among job roles
- Attrition spikes early in tenure, with a sharp peak around 5 years of experience before tapering off
- Male employees account for a larger share (63.4%) of total attrition than female employees (36.56%)

## 🛠️ Tools & Techniques

- **Power BI Desktop** — data modeling, DAX measures, and report design
- **DAX** — calculated KPIs (Attrition Rate %, Average Age, Average Experience)
- **Power Query** — data cleaning and transformation
- **Interactive slicers** — Department and Age Group filters for dynamic drill-down

## 📂 Repository Contents

```
├── HR_Analytics_Dashboard.pbix    # Power BI report file
├── dashboard_screenshot.png       # Dashboard preview image
└── README.md                      # Project documentation
```

## 📁 Dataset

This project uses the publicly available **[IBM HR Analytics Employee Attrition & Performance dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)** from Kaggle, containing employee-level data on demographics, compensation, job role, satisfaction, and attrition status.

## 🚀 How to Use

1. Clone or download this repository
2. Open `HR_Analytics_Dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Use the Department and Age Group slicers to explore attrition patterns interactively

## 📬 Connect

If you have feedback or questions about this project, feel free to reach out or open an issue in this repository.

---
⭐ If you found this dashboard useful, consider giving the repo a star!
