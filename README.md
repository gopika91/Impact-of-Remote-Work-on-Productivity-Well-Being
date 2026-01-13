# Impact-of-Remote-Work-on-Productivity-Well-Being
Analyzed the impact of remote work and workload on employee productivity and well-being using Python and Power BI. Includes data cleaning, feature engineering, EDA, interactive dashboards, and business recommendations.

## Project Overview
This project analyzes how different work arrangements (Remote, Hybrid, In-Office) and workload levels influence employee productivity and well-being. Using a realistic synthetic dataset, the analysis combines Python-based exploratory data analysis with interactive Power BI dashboards to derive actionable business insights.

The goal of the project is to demonstrate end-to-end data analysis skills, including data cleaning, feature engineering, visualization, and insight generation.

---

## Business Problem
As organizations increasingly adopt flexible work models, decision-makers need evidence on whether remote work improves productivity and employee well-being. Additionally, understanding how workload intensity affects performance and burnout risk is critical for sustainable workforce management.

This project addresses:
- Does remote work improve productivity?
- How does work mode impact employee well-being?
- How do different workload levels affect productivity and well-being?

---

## Dataset
- **Type:** Synthetic (realistic simulation)
- **Records:** ~1,500 employees
- **Key Features:**
  - Work Mode (Remote, Hybrid, In-Office)
  - Hours Worked Per Week
  - Productivity Score
  - Well-Being Score
  - Department, Team, Join Year

Synthetic data was used to avoid privacy concerns while replicating real-world workplace patterns.

---

## Data Cleaning & Preparation
Key data preparation steps included:
- Standardizing categorical values (e.g., merging WFH, Work From Home into Remote)
- Converting numeric columns stored as text
- Handling missing values using median imputation
- Correcting data types

### Feature Engineering
- Workload Level (Light, Normal, Heavy)
- Employee tenure metrics
- Indicators for high productivity and well-being risk

---

## Exploratory Data Analysis (EDA)
The analysis focused on four core relationships:
1. Productivity by Work Mode  
2. Well-Being by Work Mode  
3. Productivity by Workload Level  
4. Well-Being by Workload Level

### Key Insights
- Remote employees show higher average productivity than in-office employees
- Remote work is strongly associated with higher employee well-being
- Productivity declines gradually with heavier workloads
- Well-being declines more sharply than productivity as workload increases

---

## Power BI Dashboard
An interactive Power BI dashboard was created with two pages:
- **Page 1:** Impact of Work Mode on Productivity & Well-Being
- **Page 2:** Impact of Workload Level on Productivity & Well-Being

The dashboard allows filtering by work mode and workload level to explore trends dynamically.

---

## Recommendations
- Promote flexible work arrangements where feasible
- Monitor workload distribution to prevent burnout
- Focus on well-being indicators as early warning signals
- Encourage balanced work schedules over extended hours

---

## Projections
If implemented, these strategies are expected to:
- Sustain or improve productivity
- Improve employee well-being
- Reduce burnout and long-term attrition risk
- Support healthier and more resilient workforce performance

---

## Tools & Technologies
- **Python:** Pandas, Matplotlib
- **Power BI:** Dashboarding & data storytelling
- **Jupyter Notebook**
- **GitHub**

---
