# 📊 Remote Work Productivity and Wellbeing Tracker

# 📌 Project Overview

The **Remote Work Productivity and Wellbeing Tracker** is a **Business Intelligence (BI) dashboard developed using Microsoft Power BI**.  

This project analyzes employee survey data to understand how **remote, hybrid, and onsite work models affect employee productivity and mental wellbeing**.

The dashboard provides **interactive visual insights** about:

- Employee stress levels  
- Job satisfaction  
- Social isolation  
- Mental health conditions  
- Impact of work location  

The goal of this system is to help **HR teams and organizations make data-driven decisions** to improve employee wellbeing and productivity.

---

# ❗ Problem Statement

As remote and hybrid work models become more common, organizations face challenges in understanding their impact on employees.

There is currently a **lack of centralized data systems** to track important indicators such as:

- Stress levels
- Job satisfaction
- Social isolation
- Mental health conditions

Without proper analytics, organizations cannot easily:

- Identify high-stress employees
- Improve remote work policies
- Support employee mental health
- Optimize work environments

---

# 💡 Proposed Solution

The **Remote Work Productivity and Wellbeing Tracker** provides a **Power BI dashboard** that monitors employee wellbeing across different work models.

## Key Features

### 1️⃣ Data Integration
The system collects employee survey data including:

- Employee ID
- Age
- Gender
- Job Role
- Industry
- Work Location
- Stress Level
- Mental Health Condition
- Social Isolation Rating
- Satisfaction with Remote Work

### 2️⃣ Interactive Dashboards
The Power BI dashboard allows users to:

- Monitor employee wellbeing KPIs
- Analyze trends in stress and satisfaction
- Filter data by job role, industry, and work location
- Explore relationships between wellbeing factors

### 3️⃣ Trend Analysis
The dashboard identifies patterns such as:

- Industries with higher stress levels
- Job roles with lower satisfaction
- Impact of remote work on social isolation

### 4️⃣ Actionable Insights
These insights help organizations take **data-driven actions** to improve employee wellbeing.

---

# 🛠️ System Development Approach

The project follows a **Business Intelligence Development Lifecycle**:

1. Data Collection
2. Data Cleaning
3. Data Transformation
4. Data Modeling
5. Dashboard Development
6. Insight Generation
7. Deployment

---

# ⚙️ Technologies Used

| Technology | Purpose |
|------------|--------|
| Microsoft Power BI | Dashboard Development |
| Power Query | Data Cleaning and Transformation |
| DAX | Calculated Metrics |
| CSV Dataset | Employee Survey Data |
| Power BI Service | Dashboard Deployment |

---

# 📂 Dataset

Dataset used in this project:

**Remote Work and Mental Health Dataset**

Source:  
https://www.kaggle.com/datasets/waqi786/remote-work-and-mental-health

Dataset contains information about:

- Employee demographics
- Work location
- Stress levels
- Mental health conditions
- Social isolation ratings
- Satisfaction levels

---

# 📊 Dashboard Features

## Overview Dashboard

Provides insights such as:

- Employee distribution by work location
- Average stress levels
- Satisfaction ratings
- Industry breakdown
- Job role distribution

## Drill-Down Analysis

Users can explore deeper insights such as:

- Mental health conditions by job role
- Social isolation trends
- Satisfaction vs stress comparison
- Impact of remote work on wellbeing

---

# 🧮 Key DAX Metrics

### Average Stress Level

```DAX
Avg Stress Level = AVERAGE('Table'[Stress_Level_Number])
```

### Percentage of Satisfied Employees

```DAX
% Satisfied =
DIVIDE(
CALCULATE(COUNT('Table'[Employee_ID]), 'Table'[Satisfaction] = "Satisfied"),
COUNT('Table'[Employee_ID])
)
```

---

# 🚀 Deployment

Steps to deploy the dashboard:

1. Develop report in **Power BI Desktop**
2. Publish report to **Power BI Service**
3. Enable **Scheduled Data Refresh**
4. Share dashboard with stakeholders through:

- Web access
- Power BI workspace
- Power BI mobile app

---

# 📈 Results

The developed dashboard provides key insights such as:

- Remote employees reporting **higher stress levels**
- Slightly **lower satisfaction in remote work environments**
- Strong relationship between **social isolation and job satisfaction**
- Differences in wellbeing across **industries and job roles**

These insights help organizations create better **employee wellbeing strategies**.

---

# ✅ Conclusion

The **Remote Work Productivity and Wellbeing Tracker** demonstrates the power of **Business Intelligence tools in analyzing workforce wellbeing**.

By transforming raw survey data into meaningful visual insights, the system helps organizations:

- Detect high stress groups
- Improve remote work policies
- Provide better mental health support
- Make informed HR decisions

---

# 🔮 Future Scope

Possible future improvements include:

- **Predictive Analytics**
  - Machine learning models to predict employee burnout

- **Real-Time Data Integration**
  - Integration with collaboration tools like Microsoft Viva

- **Sentiment Analysis**
  - NLP analysis of employee feedback

- **Industry Benchmarking**
  - Compare company metrics with industry standards

- **Personalized Dashboards**
  - Individual wellbeing dashboards for employees

---

# 📚 References

Kaggle Dataset  
https://www.kaggle.com/datasets/waqi786/remote-work-and-mental-health

Microsoft Power BI Documentation  
https://learn.microsoft.com/en-us/power-bi

Research papers on **Remote Work and Employee Mental Health**

---

# 🙏 Acknowledgment

This project was developed as part of a **Capstone Project in Computer Science** to demonstrate the use of **Business Intelligence and Data Analytics** for solving real-world workplace challenges.

---
