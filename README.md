# STUDENT-PERFORMANCE-ANALYSIS-

<img width="1200" height="1200" alt="Image" src="https://github.com/user-attachments/assets/08e9c24b-83cf-40cd-9622-bc5116c2017a" />


The Student Academic Performance Dataset contains comprehensive information on student grades and subject scores across multiple classes and sections.
# Student Performance Analysis Dashboard – Portfolio Project  
**GitHub README Report**  
*Tools: Excel | Power Query | Power BI | Regression Analysis* 

---

##  Project Overview  

**Title:** *Student Performance Analysis Dashboard*  
**Dataset:** Kaggle (420 Students, 13 Columns)  
**Goal:** Analyze trends, predict success, and deliver **actionable insights** using **Excel** and **Power BI**.

---

##  What Was Done?

1. **Downloaded** dataset from Kaggle  
2. **Cleaned & transformed** data using **Power Query** in Excel  
   - Removed delimiters in column names  
   - Converted scores to **percentage format**  
3. **Built interactive visualizations** in **Power BI**  
4. **Ran regression models** to predict:  
   - Total Score from subject scores  
   - Overall Percentage from subject performance  
5. Created **interactive dashboard** with **slicers** (Grade, Section, Gender)

---

##  Key Visualizations (Power BI)

| Visualization | Insight |
|---------------|--------|
| **Average Performance by Subject** | Mathematics leads across grades |
| **Top 10 Performers** | Alyssa Richmond (93%), Jared Tate (91%) |
| **Class Performance** | Grade 3 Males: 374.88 vs Females: 368.62 |
| **Gender Distribution** | ~77% Male, 74% Female per section |
| **Performance Range** | Widest gap in Grade 1 (150.25) |
| **Head Count** | 231 Males, 189 Females |

---

##  Business Questions & Insights

| # | Question | Insight & Action |
|---|--------|------------------|
| 1 | How does gender affect performance? | **Males outperform in Grade 3** → Support males in early grades |
| 2 | Who for leadership roles? | **Alyssa Richmond (93%), Jared Tate (91%)** → Mentor program |
| 3 | How to reduce grade variation? | **Grade 1 drop (375.41 → 372.37)** → Extra tutoring in Grade 3 |
| 4 | Improve teaching? | **Mathematics drives total score** → Prioritize math resources |
| 5 | Resource allocation? | **420 students, 231 males** → Adjust Art teachers/projects |
| 6 | Narrow performance range? | **<300: Extra help, >400: Challenge** → Personalized learning |
| 7 | Subject vs Class correlation? | **R = 0.9999, R² = 0.9998** → Subject focus = class success |

---

##  Regression Analysis

###  Effect of Subjects on **Total Score**
- **Multiple R:** `1.0`  
- **R Square:** `1.0` → **Perfect fit** (Total = Sum of subjects)  
- All coefficients = `1` → Expected

###  Effect of Subjects on **Overall Percentage**
- **Multiple R:** `0.99999`  
- **R Square:** `0.99998` → **Extremely strong prediction**  
- **Mathematics Coefficient:** `1.7159E+05` → **Highest impact**  
- All **p-values = 0** → Statistically significant

> **Insight:** **10-point increase in Math** → **Largest rise in overall %**

---

##  Tools & Techniques

| Tool | Purpose |
|------|--------|
| **Excel + Power Query** | Data cleaning, transformation |
| **Power BI** | Interactive dashboard, DAX, slicers |
| **Regression (Excel)** | Predictive modeling |
| **Pivot Tables** | Trend analysis |

---

##  Project Structure (GitHub Repo)

```bash
Student-Performance-Dashboard/
│
├── data/
│   └── student_performance.csv
│
├── excel/
│   ├── cleaned_data.xlsx
│   └── regression_analysis.xlsx
│
├── powerbi/
│   └── Student_Performance_Dashboard.pbix
│
├── screenshots/
│   ├── dashboard_full.png
│   ├── regression_summary.png
│   └── top_performers.png
│
├── README.md
└── LICENSE
```

---

##  Key Takeaways

- **Mathematics = strongest predictor** of success  
- **Grade 3 males outperform** → Investigate teaching methods  
- **Grade 1 has widest gap** → Early intervention needed  
- **Top students as mentors** → Boost school culture  
- **Interactive dashboard** → Real-time decisions

---

##  Why This Project Stands Out

- Full **data pipeline**: Raw → Clean → Insights → Dashboard  
- **Statistical rigor** (p < 0.001)  
- **Interactive & intuitive** Power BI design  
- **Actionable recommendations** with evidence

---

##  Live Dashboard (Simulated)
> *Embed Power BI report in portfolio or share .pbix file*

---

##  Author  
**ORESAJO CORNELIUS**  
Data Analyst
---

> **"Turning data into smarter classrooms."**  
> *— Project Motto*

---

**Star this repo if helpful!**  
*Fork and adapt for your school.*  
