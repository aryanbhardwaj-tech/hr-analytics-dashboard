# HR Analytics Dashboard

An interactive Power BI dashboard that analyzes employee attrition and workforce demographics, helping HR teams understand who is leaving and which factors are linked to it.

## Dashboard Preview

![HR Analytics Dashboard](dashboard.png)

## Key Metrics

| Metric | Value |
|---|---|
| Total Employees | 961 |
| Total Attrition | 133 |
| Attrition Rate | 13.84% |
| Active Employees | 828 |
| Average Age | 37 |
| Average Monthly Pay | 6,281 |

## Features

- Attrition analysis by age, job role, education level and department
- Employee distribution by age group and gender
- Job satisfaction ratings by job role
- Interactive slicers for gender, marital status, education and business travel
- KPI cards for headcount, attrition, attrition rate, active employees, average age and average monthly pay

## Key Insights

- Laboratory Technicians show one of the highest attrition rates (23.94%), while Research Directors show the lowest (2.50%)
- Employees with a Bachelor's degree account for the largest share of attrition (56 of 133)
- Attrition peaks among employees in their late 20s and early 30s
- Most employees fall in the 25-44 age range, with more males than females in every age group

## Tools Used

- Power BI Desktop
- DAX
- Power Query
- Microsoft Excel (data source)

## Repository Structure

```
hr-analytics-dashboard/
├── README.md
├── dashboard.png
├── HR_Dashboard.pbit
└── Data/
```

- `HR_Dashboard.pbit`: Power BI template (no data; connect your own)
- `dashboard.png`: dashboard screenshot
- `Data/`: dataset used in the report

## How to Use

1. Open `HR_Dashboard.pbit` in Power BI Desktop.
2. Enter your data source details when prompted and click Load.
3. Use the slicers on the left to filter by gender, marital status, education and business travel.

## Dataset

The dataset is a sample HR dataset containing employee attributes such as age, gender, education, job role, department, business travel, monthly income, job satisfaction and attrition status. The file is included in the `Data/` folder.

## Author

**Aryan Bhardwaj**
GitHub: [aryanbhardwaj-tech](https://github.com/aryanbhardwaj-tech)
